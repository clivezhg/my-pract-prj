A private repo, only for Help...

(3). Regarding this line (and many similiar lines): https://github.com/clivezhg/more-lang/blob/dfbe046a6136965e1ffa85ecb3ad63079b6eedde/inc/ml_editor_postinp.php#L17
```php
	<textarea id="content_<?php echo $mlocale; ?>" name="content_<?php echo $mlocale; ?>" class="ml-local-ta" style="display:none;"><?php
```
> The reviewer required "escape every variable" when 'echo'.</blockquote>
	Firstly, in general sense, this guideline is incorrect. Because there's a very common coding pattern: store the html in a variable, change it, at last echo it, then 'esc...' will produce incorrect string.
	Secondly, there are many escaped 'echo's in More-Lang, and all unescaped are proved to be safe (i.e., their data sources are under controlled), to add 'esc...' to these safe 'echo's is useless and causing pefromance issue.
	Lastly, I inspected around 10 popular plugins, none of them does "escape every variable". Then I inspected Wordpress Core, it even does much worse than More-Lang, it doesn't 'esc...' some uncontrolled data.
So, this guideline looks a little unrealistic (too awkward for most developers to implement), the reviewer was giving very very unfair task to More-Lang...but of course, the reviewer denied (without any reasonable explanation).</div>
