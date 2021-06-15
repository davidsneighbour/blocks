# Form Generator

## Form forwarding services

### [Formspree](https://formspree.io/)

#### Automatically

- [ Honeypot spam filtering](https://help.formspree.io/hc/en-us/articles/360013580813-Honeypot-spam-filtering)

#### Manually

- Set `.type` in the configuration to `"formspree"`.
- Make sure to name your field for the users email `_replyto` or `email` so it gets [added as return address to all 
  email notifications](https://help.formspree.io/hc/en-us/articles/360012262774-Email-Reply-To-address-).
- Either add a text field or a hidden field named `_subject` to set the notification emails subject line.
- Add one of the following field names to define the visitors name: `_name`, `name`, `_fname`, or `_lname`.
- Add one of the following field names to define the message field: `_message`, `message`, or `msg`.
- Read more about [special tags in Formspree](https://help.formspree.io/hc/en-us/articles/360062302854-Special-Fields).
- Read more about [localisation rules](https://help.formspree.io/hc/en-us/articles/360013468374-Localization-and-translation).

#### Formspree TODO

- [AJAX form submision](https://help.formspree.io/hc/en-us/articles/360013470814-Submit-forms-with-JavaScript-AJAX-) 
  [[2](https://help.formspree.io/hc/en-us/articles/1500009404742-How-to-clear-a-form-after-submission)]
