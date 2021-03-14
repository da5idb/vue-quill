# Props

**`content`** : Contents for the editor, Can be plain `string`, `html` or `Delta` object, see [Quill Delta docs](https://quilljs.com/docs/delta/) for more details.

**`enable`** : Set ability for user to edit, via input devices like the mouse or keyboard.

**`readOnly`** : If *true*, the editor won't allow changing its contents. Wraps the Quill [`disable` API](https://quilljs.com/docs/api/#disable). 

**`placeholder`** : The attribute to specifies a short hint that describes the expected value of an input field (e.g. a sample value or a short description of the expected format).

**`options`** : To configure Quill options see [the docs options](https://quilljs.com/docs/configuration/#options) for more details

**`theme`** :  The name of the theme to apply to the editor, Quill features two offically supported themes: `snow` and `bubble`. Pass `""` to use the minimal core theme. See the [docs on themes](https://quilljs.com/docs/themes/) for more information on including the required stylesheets. 

**`toolbar`** : Toolbar options to configure the default toolbar icons using an array of format names. [see above](##Toolbar)