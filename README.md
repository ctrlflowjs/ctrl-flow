<p align="center" style="margin-bottom: -5px">
  <img width="245" height="70" src="./docs/assets/Logo.PNG">
</p>

ctrl+flow is the open source **user automation** framework.

#### What is user automation? 

User automation means enabling users to automate parts of an application by letting them choose a triggering event and a series of actions to perform. It allows users an advanced level of control of app logic without writing code or needing developer support. It's found in many popular enterprise tools like Airtable, Slack, and Trello, and with ctrl+flow it can easily be added to any Node.js web app.

## Demo

[demo.ctrlflowjs.com](https://demo.ctrlflowjs.com/)

The actions and events available in this demo are purely illustrative examples, your app would contain components you create or install from third party packages.

## Getting Started

> The project is v0 and still in early development. v0 releases are expected to run (please give it a try and share feedback!), just be warned that there will be bugs, and preserving backwards compatibility is not yet a priority.

Adding ctrlflow to your app is straight forward:

1) Install it server-side `npm install @ctrlflow/core`
2) Define your app with modules and a storage provider ([example](https://github.com/ctrlflowjs/ctrlflow/blob/main/examples/crm/src/ctrlflow/app.js))
3) Start the app runtime and plug in the UI server ([example](https://github.com/ctrlflowjs/ctrlflow/blob/main/examples/crm/src/server.js))

## License

ctrl+flow is free and open source software with an MIT license. A pro license will also be available with a support plan and advanced controls for larger organizations.
