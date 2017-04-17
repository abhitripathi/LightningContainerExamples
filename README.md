# LightningContainerExamples

This repo contains several example LCC components.

The examples are organized by UI framework, then by programming language and finally by component. For now, there are only ReactJS/javascript examples in this repo. Going forward, we will add AngularJS examples and typescript examples.

Each example is standalone and contains all of the files necessary to build, deploy and run that example.

Some of the examples were bootstrapped using Facebook's create-react-app tool. The "basic", "custom-attribute", "send-receive-messages" and "soql" examples were all bootstrapped using create-react-app.

Some of the examples were not bootstrapped using any tool and were instead manually assembled. The "Realty" example was not bootstrapped using any tool. We intend to upgrade such examples to be bootstrapped from tools such as create-react-app.

For each of the examples, it is necessary to configure a Salesforce org for custom Lightning component use and development before deploying or running the examples. This configuration is the exact same configuration that would be necessary for any custom Lightning component use or development:

1. Create and deploy a my-domain for the org
2. Enable Lightning for the org
3. Switch to Lightning Experience for the user who will be deploying and running the examples.

After configuring the Salesforce org, clone this repo to a local machine. Then, select an example to build, deploy and run. For each example, change directories into the top level directory for the example (e.g. "basic", "custom-attribute") and execute npm commands from that top level directory. Each example's top level directory contains README file(s) with instructions for building, deploying and running that example. For the examples that were bootstrapped using a tool, there will be the README file that was generated by the bootstrap tool and there will be a README file provided by Salesforce.
