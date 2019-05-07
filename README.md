# ![LOGO](logo.png) Text Analytics Client **flow**ground Connector

## Description

A generated **flow**ground connector for the Text Analytics Client API (version v2.1-preview).

Generated from: https://api.apis.guru/v2/specs/azure.com/cognitiveservices-TextAnalytics/v2.1-preview/swagger.json<br/>
Generated at: 2019-05-07T17:37:48+03:00

## API Description

The Text Analytics API is a suite of text analytics web services built with best-in-class Microsoft machine learning algorithms. The API can be used to analyze unstructured text for tasks such as sentiment analysis, key phrase extraction and language detection. No training data is needed to use this API; just bring your text data. This API uses advanced natural language processing techniques to deliver best in class predictions. Further documentation can be found in https://docs.microsoft.com/en-us/azure/cognitive-services/text-analytics/overview

## Authorization

Supported authorization schemes:
- API Key
## Actions

### The API returns a list of recognized entities in a given document.

> The API returns a list of recognized entities in a given document. To get even more information on each recognized entity we recommend using the Bing Entity Search API by querying for the recognized entities names. See the <a href="https://docs.microsoft.com/en-us/azure/cognitive-services/text-analytics/text-analytics-supported-languages">Supported languages in Text Analytics API</a> for the list of enabled languages.The API returns a list of known entities and general named entities ("Person", "Location", "Organization" etc) in a given document. Known entities are returned with Wikipedia Id and Wikipedia link, and also Bing Id which can be used in Bing Entity Search API. General named entities are returned with entity types. If a general named entity is also a known entity, then all information regarding it (Wikipedia Id, Bing Id, entity type etc) will be returned. See the <a href="https://docs.microsoft.com/en-us/azure/cognitive-services/text-analytics/how-tos/text-analytics-how-to-entity-linking#supported-types-for-named-entity-recognition">Supported Entity Types in Text Analytics API</a> for the list of supported Entity Types. See the <a href="https://docs.microsoft.com/en-us/azure/cognitive-services/text-analytics/text-analytics-supported-languages">Supported languages in Text Analytics API</a> for the list of enabled languages.

*Tags:* `Entities`

### The API returns a list of strings denoting the key talking points in the input text.

> See the <a href="https://docs.microsoft.com/en-us/azure/cognitive-services/text-analytics/overview#supported-languages">Text Analytics Documentation</a> for details about the languages that are supported by key phrase extraction.

*Tags:* `Key Phrases`

### The API returns the detected language and a numeric score between 0 and 1.

> Scores close to 1 indicate 100% certainty that the identified language is true. A total of 120 languages are supported.

*Tags:* `Detect Language`

### The API returns a numeric score between 0 and 1.

> Scores close to 1 indicate positive sentiment, while scores close to 0 indicate negative sentiment. A score of 0.5 indicates the lack of sentiment (e.g. a factoid statement). See the <a href="https://docs.microsoft.com/en-us/azure/cognitive-services/text-analytics/overview#supported-languages">Text Analytics Documentation</a> for details about the languages that are supported by sentiment analysis.

*Tags:* `Sentiment`

## License

**flow**ground :- Telekom iPaaS / azure-com-cognitiveservices-text-analytics-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
