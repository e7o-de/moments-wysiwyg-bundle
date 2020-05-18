# Copyright

This is just a convinience bundle for TinyMCE. It wraps the repository
https://github.com/tinymce/tinymce into a bundle. TinyMCE is licensed under
LGPL v2.1 (https://github.com/tinymce/tinymce/blob/develop/LICENSE.TXT).

This bundle uses the self-hosted version (https://www.tiny.cloud/get-tiny/self-hosted/).
If you wanna go with 3rd-party requests/libs (remember: they might be blocked
by users due to privacy reasons), ignore this bundle and use their recommendation:

```html
<script src="https://cdn.tiny.cloud/1/no-api-key/tinymce/5/tinymce.min.js" referrerpolicy="origin"></script>
<script type="application/javascript">tinymce.init({selector: 'textarea'});</script>
```

# Current version

This package contains 5.2.2.

# Contribute?

For fixes related to the editor component, see their Github project.

# Usage

```html
<script type="application/javascript">tinymce.init({selector: 'textarea'});</script>
```

