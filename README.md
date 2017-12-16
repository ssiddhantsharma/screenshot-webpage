## *WEBPAGE-SCREENSHOT-USING-API 


***This web application uses thum.io API to create awesome, rich screenshots of the websites the user has mentioned!
***This project was built using [Thum.io API](https://www.thum.io/) :bulb:

Supporting Material-UI

Material-UI is an MIT-licensed open source project. It's an independent project with ongoing development made possible thanks to the support of these awesome backers. If you'd like to join them, please consider:

Become a backer or sponsor on Patreon.
Become a backer or sponsor on OpenCollective.
Your contributions, donations, and sponsorship allow us to build a sustainable organization. They directly support office hours, continued enhancements, great documentation and learning materials!

What's the difference between Patreon and OpenCollective?

Funds donated via Patreon directly support Olivier Tassinari's work on Material-UI. Funds donated via OpenCollective also support Olivier, but will be shared amongst other contributors and pay for operating expenses. These funds are managed transparently through the OpenCollective website. Your name/logo will receive proper recognition and exposure by donating on either platform.

Gold Sponsors

Gold Sponsors are those who have pledged $500/month and more to Material-UI.

via Patreon

via OpenCollective

         

Installation

Material-UI is available as an npm package.

Stable channel (v0.x)

npm install --save material-ui
Pre-release channel (v1-beta)

npm install --save material-ui@next
Please note that @next will only point to pre-releases; to get the latest stable release use @latest instead.

Usage (v1-beta)

Here is a quick example to get you started, it's all you need:

import React from 'react';
import { render } from 'react-dom';
import Button from 'material-ui/Button';

function App() {
  return (
    <Button>
      Hello World
    </Button>
  );
}

render(<App />, document.querySelector('#app'));
Yes, it's really all you need to get started as you can see in this live and interactive demo:

Edit Button

Questions

For how-to questions and other non-issues, please use StackOverflow instead of Github issues. There is a StackOverflow tag called "material-ui" that you can use to tag your questions.

Examples

Are you looking for an example project to get started? We host some.

Documentation

Check out our documentation website.

Contributing

We'd greatly appreciate any contribution you make. :)

Changelog

Recently Updated? Please read the changelog.

Roadmap

The future plans and high priority features and enhancements can be found in the ROADMAP.md file.

Thanks



Thank you to BrowserStack for providing the infrastructure that allows us to test in real browsers.

License

This project is licensed under the terms of the MIT license.
