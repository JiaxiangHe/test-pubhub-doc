# Getting Started

_>This page is necessary. Do not delete._ 

_>The getting started guide is designed to help a developer transition from being a newbie with your API to comfortably performing a basic task. For more details on documenting a getting started guide, refer to the ["Quick Start Section"](https://apistyleguide.cisco.com/#apix-documentation/quick-start-section) of the API style guide. The guide is formally referred to as a "Quick Start Guide"._

_> Provide an introduction of what the quick start guide helps them achieve._

The following sections introduce you to the XYZ API resources and provide instructions to make your first API request. Learn how to set up an account, obtain an API token, and retrieve the resources. The examples demonstrate using the command line with cURL and using Python code.

_> Provide the high-level overview of the API resources. The following is the example text:_

The API supports standard REST methods, including POST, GET, and DELETE operations through HTTPS. All payloads to and from the REST interface must be in JSON format. The following is high-level description of the API resources:

**User** - Represents an Agent, Supervisor, or Administrator.
* Get User Details.
* Change User state (for example, Sign In, Sign Out, Ready, Not Ready, and so on).
* Get User's Dialogs.

**Queue** - Represents a queue (or skill group in Unified CCE)
* Get Queue Details.
* Get List of Queues for a User.


_> Provide links to setup a base URL. Below, you can see the example text._

## Base URL

Every API request begins with the following base URL.

```
https://api.xyzdashboard.io/api/v1
```


_> If you have a Sandbox, provide the Sandbox link so that developers can try out the API. Also, provide a link to the "Sandbox" page in the Developer Resources page for users to learn more about the Sandbox. Below, you can see the example text._

## Sandbox

DevNet provides free hosted development environments, known as [DevNet Sandboxes](https://developer.cisco.com/site/sandbox/), for integrating and working with Cisco technologies. You can try out the API using reservation-based Sandboxes (privately configured for you) or Always-on Sandboxes (publicly configured, but with limited access). View the list of available [XYZ Sandboxes](../resources/sandbox.md).


_> Provide example for authentication. Below, you can see the example text._

## Authorization

In addition to the path URL, add an `Authorization` header to every API request using the following format.

```
... show how to do this using cURL and Python ...
```

Read more about authenticating, including generating an API token [here](authentication.md).

_> Some APIs require a developer to enable the API by logging into the product dashboard and retrieving a token. In that case, provide step-by-step instruction on how to log in to the product and enable the API. For an example, refer to [ThousandEyes Authentication](https://developer.cisco.com/docs/thousandeyes/authentication/)._

_> Then, write the top three things you can do with the API. For example, find a user, start chatting with the user, or create a new room to chat in. Or maybe you want to discover a configuration, load a new configuration, and deploy a changed configuration. Whatever it is your users want to do right away with your API, give them quick examples to try out._

## 1. Obtain a List of Networks

First, obtain a list of networks. You will need the network ID for the next steps.

### Request

... step-by-step continues for your API ...

### Response

... show an example response ...

## 2. Retrieve the Details of a Network

Using the response from the previous step of listing networks, retrieve the details of a network instance...

### Request

... step-by-step continues for your API ...

### Response

... show an example response ...

## 3. Modify a Network

Using the identifier from the network retrieved previously, modify it so that the description is different....

### Request

... step-by-step continues for your API ...

### Response

... show an example response ...

## 4. Retrieve the Updated Details of a Network

Finally, retrieve the updated details of a network to see the recent modifications...

### Request

... step-by-step continues for your API ...

### Response

... show an example response ...


_> Offer Postman Collections if there's a group of easy tasks to try._

## Try It Out Using Postman Collections

Prefer to use Postman rather than code or the command line? Check out our [Postman Collections](../resources/postman.md). 

_> Additional resources and Cisco product examples:_

* [Cisco API Guidelines: Recommendations for Getting Started Documentation](https://developer.cisco.com/api-guidelines/apix-documentation/#getting-started-section)
* [Meraki: Getting Started](https://developer.cisco.com/meraki/api-v1/#!getting-started/base-uri)
* [Cisco XDR Getting Started](https://developer.cisco.com/docs/cisco-xdr/getting-started/)
