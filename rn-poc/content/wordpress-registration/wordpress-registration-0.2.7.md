+++
date = "2015-02-02T12:33:42-07:00"
title = "Wordpress Registration 0.2.7"

categories = [
    "WordPress Registration"
]

+++

| Change                              |   | Impact  |
| ----------------------------------- |---| --------|
| {{< change-badge new="true" >}}  | The plugin now modifies the language setting for Registration widgets to match the language setting of the site (this may affect translations with names that do not correspond to ISO naming conventions). | {{< impact-badge automatic="true" >}} |
| {{< change-badge fixed="true" >}}  | The plugin now triggers the `wp_login` action when visitors log in through Janrain. | {{< impact-badge automatic="true" >}} |
