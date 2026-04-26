# valmail

An email validator that will validator multiple fields of an email sent from a click in a gmail inbox


## Functional Features

### Browser

An browser extension that will have the following functionalities

- [ ] When click on email in gmail inbox, will access it raw contents and compute validations against the browser api
  - [ ] Date Validation
  - [ ] Region Validation
  - [ ] Network Infrastructure used
  - [ ] Intercept any api call and record it to send to server
- [ ] Send all computed validation to a backend service

### BackendService

- [ ] It will make a tsa register of raw contents and computed metadata of email
- [ ] Will make the same validation of browser side on server side
