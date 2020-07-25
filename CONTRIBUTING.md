# Contributing

We are open to, and grateful for, any contributions made by the community.

## Reporting Issues and Asking Questions

Before opening an issue, please search the [issue tracker](https://github.com/jeffbski/redux-logic-examples/issues) to make sure your issue hasn’t already been reported.

### Bugs and Improvements

We use the issue tracker to keep track of bugs and improvements to redux-logic itself, its examples, and the documentation. We encourage you to open issues to discuss improvements, architecture, theory, internal implementation, etc. If a topic has been discussed before, we will ask you to join the previous discussion.

### Getting Help

If you cannot find your answer in the README or the docs, please check the issues to see if anyone has asked a similar question and if not please post an issue.

[GitHub issue tracker for redux-logic](https://github.com/jeffbski/redux-logic-examples/issues)

### Help Us Help You

On both websites, it is a good idea to structure your code and question in a way that is easy to read to entice people to answer it. For example, we encourage you to use syntax highlighting, indentation, and split text in paragraphs.

Please keep in mind that people spend their free time trying to help you. You can make it easier for them if you provide versions of the relevant libraries and a runnable small project reproducing your issue. You can put your code on [JSBin](http://jsbin.com) or, for bigger projects, on GitHub. Make sure all the necessary dependencies are declared in `package.json` so anyone can run `npm install && npm start` and reproduce your issue.

## Development

Visit the [issue tracker](https://github.com/jeffbski/redux-logic-examples/issues) to find a list of open issues that need attention.

Fork, then clone the repo:

```
git clone https://github.com/your-username/redux-logic-examples.git
```

### Building

redux-logic-examples demonstrate various concepts and best practices.

When adding a new example, please adhere to the style and format of the existing examples, and try to reuse as much code as possible. For example, `index.html`, `server.js`, and `webpack.config.js` can typically be reused.

#### Building and Testing the Examples

To build and test the official Redux examples, run the following:

```
npm run build:examples
npm run test:examples
```

Not all examples have tests. If you see an example project without tests, you are very welcome to add them in a way consistent with the examples that have tests.

### Sending a Pull Request

For non-trivial changes, please open an issue with a proposal for a new feature or refactoring before starting on the work. We don’t want you to waste your efforts on a pull request that we won’t want to accept.

On the other hand, sometimes the best way to start a conversation _is_ to send a pull request. Use your best judgement!

In general, the contribution workflow looks like this:

- Open a new issue in the [Issue tracker](https://github.com/jeffbski/redux-logic-examples/issues).
- Fork the repo.
- Create a new feature branch based off the `master` branch.
- Make sure all tests pass and there are no linting errors.
- Submit a pull request, referencing any issues it addresses.

Please try to keep your pull request focused in scope and avoid including unrelated commits.

After you have submitted your pull request, we’ll try to get back to you as soon as possible. We may suggest some changes or improvements.

Thank you for contributing!
