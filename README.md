angular-editinplace
===================

Simple edit-in-place directive for Angular.js

You can choose between input or textarea, add or not label element, and pass attributes for input element (which will be compiled, that's mean you can pass directives like ng-required or whatever).

Example:
```<h2 class="form__field"
        edit-in-place="offer.template.title"
        label="{{ i18n.offer.create.title }}"
        default-active="true"
        input-attrs="{
            'placeholder': i18n.offer.create.example.title,
            'ng-required': true,
            'ng-maxlength': 50
        }"
        title="{{ i18n.offer.create.title }} - {{ i18n.offer.create.clickToEdit }}"></h2>```
