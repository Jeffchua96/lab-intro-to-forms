# Introduction to Forms Lab

In this lab, you will have an opportunity to build a form in HTML.

## Assessment Setup

### Getting started

1. Fork and clone this repository.

1. Navigate to the cloned repository's directory on your command line. Then, run the following command:

   ```
   npm install
   ```

   This will install the libraries needed to run the tests.

1. Open up the repository in VSCode. Follow the instructions below to complete the Lab.

### Tests

To run the tests, you can run the following command from the command line. You will need to be in the root directory of your local directory.

```
npm test
```

This will open the Cypress testing window, where you can click to run an individual suite of tests or all of the tests at once.# Question Three

## Instructions

Make a file `payment-form.html` that displays a form to enter payment information. It should like similar to this:

![paymentFromImage](./images/paymentForm.png)

### Requirements

In addition to looking similar to the image above, make sure you meet the following requirements:

- [ ] Your submit button should be an `input` element, with the text `Submit Payment`.

- [ ] You should have all four radio buttons listed above.

- [ ] The first radio button should be `checked` by default.

- [ ] When a radio button is clicked, the other radio buttons should be de-selected.

- [ ] The Name field should be a text input, have a corresponding label tag, and have an id of `name`.

- [ ] The Email field should be an email input, have a corresponding label tag, and have am id of `email`.

- [ ] The Dropdown should include four options: "Visa", "Mastercard", "American Express", and "Discover".

- [ ] The Dropdown option's values should be "visa", "mastercard", "american-express", and "discover".

- [ ] The Credit Card field should be a `tel` type and have a placeholder of `xxxx xxxx xxxx xxxx`.

- [ ] The Expiration Date field should be a `text` type, have a corresponding label tag, and should have an id of `expiration-date`.

### Bonus

In Chrome Developer tools, there is a tab called `LightHouse`. Run a lighthouse audit for `Accessiblity` and `Best Practices` (deselect other options).

Use the audit to update your form so that you get a score of 100% For accessibility and best practices.

![lighthouse bonus](./images/chromeLighthouseBonus.png)
