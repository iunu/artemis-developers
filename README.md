## Welcome to the Artemis developer's portal!

If you're a developer working on integrating with the Artemis API, the team of developers at Artemis has aggregated some documentation that can help you get started and work with our code.

### Documentation

- [API Documentation](https://portal.artemisag.com/api/docs)

The most current version of the Artemis API is v3 and it's documented on SwaggerHub.

 - [The Artemis API gem on GitHub](https://github.com/artemis-ag/artemis_api)
 - [And also on RubyGems](https://rubygems.org/gems/artemis_api)

 We also have an API wrapper gem that you can use in your Ruby app to make calling our API easier and more readable. The documentation and source code is available on GitHub.

 Note: Since the gem is still under active development, if you're worried about having the most up to date version of it, you can include it in your Ruby app directly from the GitHub repo by using this line in your gemfile:

 ```ruby
 gem 'artemis_api', :git => 'https://github.com/artemis-ag/artemis_api'
 ```

### OAuth 2.0

The Artemis API v3 uses OAuth 2.0 for authorization. In order to set up an OAuth 2.0 application and get your Artemis app id and app secret, you'll need your Artemis account to be flagged as a developer account. If you're not flagged as a developer account and you need to be, contact your Artemis representative or email [Jon Dayton](mailto:jdayton@iunu.com) and we'll help you get set up.

If you already have a developer account, you can create your OAuth application from the Artemis settings page and it will provide you with your app id and app secret.

It's possible to test the API calls directly on the [SwaggerHub documentation page](https://portal.artemisag.com/api/docs) by creating an OAuth application for Swagger tests using this URL as the callback URL: `https://app.swaggerhub.com/oauth2_redirect` You'll then be able to Authorize on SwaggerHub using your app id and app secret and use their "Try it out" feature within the documentation.

If you just need to access your authorization code directly, you can add `urn:ietf:wg:oauth:2.0:oob` as an additional callback url to your OAuth application. Then, clicking the Authorize button directly beside it on your application show page will just provide you directly with an authorization code.

### Minimum System Requirements

[View minimum system requirement information here.](https://agrilyst.zendesk.com/hc/en-us/articles/360035814792-Requirements-for-Artemis-) This covers the Artemis web app, as well as both the Apple and Android versions of the mobile app.

### Support

If you need help getting set up with the Artemis API or you encounter any problems with the provided documentation, the Artemis team is here to help. Please contact [Jon Dayton](mailto:jdayton@iunu.com) with any questions or concerns you may have.
