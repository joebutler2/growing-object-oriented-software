We should be taught not to wait for inspiration to start a thing. Action always generates inspiration. Inspiration seldom generates action.

—Frank Tibolt

Start by automating the build and deployment process. Sounds odd for a nascent system but it's important to do so, because "later" means "never".

The authors have seen projects canceled after months of work since they couldn't reliable deploy the system.

"Feedback is a fundamental tool"

## Walking skeleton

It's difficult to build the first feature while at the same time trying to automate all of these processes. To work around this paradox build the simplest thing possibly that can be automated. For example, with a web application backed by a database you can display a simple web page that retrieves a couple of fields from the database.

They describe acceptance / end-to-end tests as something that will build the app, deploy it, then run the tests in a production-like environment.

Another benefit to automating all of this upfront is that it reveals organizational dependencies. So if it takes several weeks and a few signatures (from managers and operational folks) then that it something you want to know sooner rather than later.

When working on the "walking skeleton" don't worry about writing the best, most expressive test. At this point the value is setting up automation around the system.

For later tests we should "write the test you want to read." (more on page 42).





