[![Build Status](https://travis-ci.org/cherukumilli/dc-email-input.svg?branch=master)](https://travis-ci.org/cherukumilli/dc-email-input)

_[Demo and API Docs](https://cherukumilli.github.io/dc-email-input)_


##&lt;dc-email-input&gt;


`<dc-email-input>` is a single-line text field with Material Design styling
for entering an email address.

This field has the mail icon as prefix and clear icon as the suffix.

    <dc-email-input></dc-email-input>

It may include an optional label, which by default is "Email".

    <dc-email-input label="your email address"></dc-email-input>

### Validation

The input can be automatically validated as the user is typing by using
the `auto-validate` and `required` attributes. For manual validation, the
element also has a `validate()` method, which returns the validity of the
input as well sets any appropriate error messages and styles.

See `Polymer.PaperInputBehavior` for more API docs.

### Styling

See `Polymer.PaperInputContainer` for a list of custom properties used to
style this element.
