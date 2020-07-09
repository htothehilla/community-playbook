# 👥 📕 Mozilla Voice Community Playbook V1.0

- *Last update: July 9th 2020*
- *[Edit this document and propose a change](https://github.com/Common-Voice/community-playbook/edit/master/README.md)*
- *Content coordination: Rubén Martín <rmartin@mozilla.com>*
- *[License](./LICENSE)*

Mozilla Voice communities empower the collection of machine-learning based voice technologies -- including software, tools, and data -- that Mozilla stands behind.

## Goals for this playbook

* Provide people interested in contributing to Mozilla Voice goals and mission with clear guidelines and expectations on how to set up and run a self-sustaining Mozilla Voice community.
* Unify existing community knowledge previously documented in different places.
* Be the central place to understand the whole voice community journey.
* Communicate what brings value to the project and how communities can support it.


## Participation Guidelines

Mozilla Voice communities are governed by Mozilla's code of conduct and etiquette guidelines, we take this very seriously and no violations are tolerated.

We encourage you to please read[ Mozilla Community Participation Guidelines](https://www.mozilla.org/about/governance/policies/participation/) before contributing to this project.

For more information on how to report violations of the Community Participation Guidelines, please read our '[How to Report](https://www.mozilla.org/about/governance/policies/participation/reporting/)' page.


## Governance

Mozilla Corporation owns the overall Mozilla Voice project governance and is the ultimate decision maker for its direction and goals. It’s also in charge of the development of some tools and channels described here to support our communities.

The voice communities are self-organized, and you don’t need to ask for permission to participate or mobilize any of these communities in your language. All the data generated by communities is published under open licences.

Some community roles exist formally and informally, and they all should follow [the Mozilla leadership shared agreements](https://discourse.mozilla.org/t/what-s-next-for-volunteer-leadership-in-2018-shared-agreements/25091).

## The Voice communities

Mozilla Voice has a variety of communities that support the project in different important areas, they are usually grouped by language.

The work done by these communities advance a language from not having a presence in Mozilla Voice at all to being able to generate a functional STT model which is able to understand how people speak.

<table>
  <tbody>
    <tr>
      <td>📝</td>
      <td><strong><a href="#-text-corpus">Text corpus</a></strong>
      <p>Gathering, validating and processing public domain sentences.<br />
      <a href="#our-purpose">Purpose</a> - <a href="#who-we-are">Who we are</a> - <a href="#whats-success">Success</a> - <a href="#how-to-join">How to join</a> - <a href="#what-we-do">What we do</a> - <a href="#roles">Roles</a> - <a href="#channels">Channels</a></p></td>
    </tr>
    <tr>
      <td>🗣</td>
      <td><strong><a href="#-voice-corpus">Voice corpus</a></strong>
      <p>Recording and validating voices to create a public domain dataset.<br />
      <a href="#our-purpose-1">Purpose</a> - <a href="#who-we-are-1">Who we are</a> - <a href="#whats-success-1">Success</a> - <a href="#how-to-join-1">How to join</a> - <a href="#what-we-do-1">What we do</a> - <a href="#roles-1">Roles</a> - <a href="#channels-1">Channels</a></p></td>
    </tr>
    <tr>
      <td>🌍</td>
      <td><strong><a href="#-localization">Localization</a></strong>
      <p>Adapting the project tools and materials to be understood by a specific audience.<br />
      <a href="#our-purpose-2">Purpose</a> - <a href="#who-we-are-2">Who we are</a> - <a href="#whats-success-2">Success</a> - <a href="#how-to-join-2">How to join</a> - <a href="#what-we-do-2">What we do</a> - <a href="#roles-2">Roles</a> - <a href="#channels-2">Channels</a></p></td>
    </tr>
    <tr>
      <td>🤖</td>
      <td><strong>Model training (TBD)</strong>
      <p>Using our text and voice datasets to train and optimize STT models in specific languages using machine learning.</p></td>
    </tr>
  </tbody>
</table>


👥 As you can read on this playbook, you will need a multidisciplinary team of committed people to support your language journey.

🔨 Make sure you check the _required skills_ for each section and look for people who can fit.

💬 Check the channels section to learn how to set up your local forums and chat to communicate with other people in your language.

ℹ️  _Note: Mozilla’s focus is to optimize this project, tools and communities for the goals and measures of success described in this document. We welcome small and minority language communities, and we understand these goals may seem out of reach. In that case, feel free to share with us how they are different for you. Nevertheless, we welcome all language communities!_


## 📝 Text corpus

### Our purpose

Collect or generate text corpus under public domain licence that can be read by people to facilitate their voice donations.

### Who we are

We are a community of text collectors and creators, always looking for places with text corpora we can extract and process so it can be transformed into short and simple sentences for people to read.

### What’s success

Generate as many sentences as possible in our languages. Having more sentences allows contributors to donate more hours of voice data.

* 5,000 sentences 	_allow_ 	5,5 hrs of voice
* 9,000 sentences 	_allow_ 	10 hrs of voice
* 90,000 sentences	_allow_ 	100 hrs of voice
* 1,800,000 sentences _allow_ 	2000 hrs of voice

⚠️ _You will need at least 5000 validated sentences to have your language enabled for voice contributions on our voice collection site._

### How to join

Anyone can join this community. Join our [discourse forums](https://discourse.mozilla.org/c/voice/) or our [matrix chat](https://chat.mozilla.org/#/room/#common-voice:mozilla.org), introduce yourself and jump into our sentence tools right away.

### What we do

#### **Sentence extraction**

We have developed [a tool to extract sentences](https://github.com/Common-Voice/cv-sentence-extractor) from large sources of public domain text, with a focus easy-to-read corpus and Wikipedia.

This is the easiest and fastest way to get more than a million sentences as soon as possible for your language.

<p style="text-align: right">
ℹ️ <em>Please read <a href="https://github.com/Common-Voice/cv-sentence-extractor#common-voice-sentence-extractor">the tool documentation</a> on how to generate specific rules for your language. </em></p>

⚠️ _Important: Due to legal reasons Mozilla needs to be the one running the final extraction, so please don’t do any manual processing to the resulting extraction during your tests. We can apply manual clean-up after the final version is generated by Mozilla._

🔨 _Skills required to help: Command line usage and git, familiar with regular expressions._

#### **Sentence collection**

We have also created a [sentence collection tool](https://common-voice.github.io/sentence-collector/#/) that allows contributors to collect and validate sentences created by the community. You can use this tool also to import and clean-up small-to-medium-sized public domain corpus you have found or collected.

ℹ️ _Please read [the collector how-to](https://common-voice.github.io/sentence-collector/#/how-to) before using this tool and check the [community guidelines on how to validate sentences](https://discourse.mozilla.org/t/discussion-of-new-guidelines-for-uploaded-sentence-validation/37718)_.

🔨 _Skills required to help: Strong grammar knowledge of the target language you are contributing to._

#### **Large corpus validation**

If you have found an existing public domain corpus bigger than 100K sentences, we have an independent process to handle it, since we understand that manual validation using the sentence collector is not ideal.

ℹ️ _Please create a new topic on [our ](https://discourse.mozilla.org/c/voice/)discourse, so we can evaluate if your corpus fits the licence and size requirements to run this process._

🔨 _Skills required to help: Expertise processing and cleaning up text, linguistics/language expertise to check the quality of the resulting sentences._

#### **Tooling development**

Contributors also develop, maintain and update the sentence extractor and collector code.

* Sentence Extractor: 🐞 [Open issues](https://github.com/Common-Voice/cv-sentence-extractor/projects/1?fullscreen=true) - 🔨 _Skills needed: Rust_
* Sentence Collector: 🐞 [Open issues](https://github.com/Common-Voice/sentence-collector/projects/2?fullscreen=true) - 🔨 _Skills needed: React, JavaScript (and soon Node.js)_

### Roles

These are some roles you can take as part of this community.

* Text searcher - Find and connect with sources and organizations that have or are willing to donate text corpus under public domain licence.
* Text processor - Cleaning up the raw text corpus to apply [our sentences requirements](https://common-voice.github.io/sentence-collector/#/how-to).
* Text creator - Generate your own sentences and release them under public domain.
* Validator - Help validate and review existing cleaned-up sentences.
* Mobilizer - Help people in the community to get started and keep contributing.
* Developer - Develop, maintain and update the sentence tooling.

### Channels

* [Common Voice discourse](https://discourse.mozilla.org/c/voice/) category.
* [Common Voice matrix](https://chat.mozilla.org/#/room/#common-voice:mozilla.org) chat room.
* [Sentence Extractor matrix](https://chat.mozilla.org/#/room/#common-voice-sentence-extractor:mozilla.org) chat room.
* [Common Voice project announcements](https://discourse.mozilla.org/tags/c/voice/announcements).

💬 If your language already exists on Common Voice, make sure you [check and join the local discourse](https://voice.mozilla.org/about#get-involved) and matrix room. If that’s not the case, please create a new topic [on discourse](https://discourse.mozilla.org/c/voice/239) asking for one to be created.

## 🗣 Voice corpus

### Our purpose

Donate and validate our voices under [public domain](https://voice.mozilla.org/terms) licence to generate a dataset usable by Speech to Text technologies to train models in different languages democratizing voice technology.

### Who we are

We are a community of voice tech enthusiasts, who want to help collect and generate a large dataset of public domain voices that can be freely used to train [Speech to Text technologies](https://github.com/mozilla/DeepSpeech).

### What’s success

Collect and validate as many voices as possible in our languages. Having more voices validated allows us to then train more advanced STT models.

* At least 1,000 unique speakers per language.
* 2,000 hours of voice validated to train a near-human general STT model.
* 10,000 hours of voice validated for a very high quality, general, large vocabulary, continuous speech recognition model.

![Data quantities](/assets/img/data-quantities.png)

### How to join

Anyone can join this community. Join our [discourse forums](https://discourse.mozilla.org/c/voice/) or our [matrix chat](https://chat.mozilla.org/#/room/#common-voice:mozilla.org) and introduce yourself, jump into [Common Voice site](https://voice.mozilla.org), get familiar with it and start donating your voice.

🔨 _You don’t need any specialized skill to contribute to this community, you only need to be able to speak into a microphone or listen to audio clips._

### What we do

⚠️ _In order to have a language enabled on our site, you will need at least 5000 validated sentences, see previous section about text corpus for reference._

#### **Voice donation**

We have developed a site that allows you to [donate your voice](https://voice.mozilla.org/speak) by reading sentences collected by the community.

Feel free to create an account to track your progress and add more information on your profile about your voice. Demographic information helps us balance the dataset, giving machine learning researchers and engineers a way to train models that represent better the speakers of the language.

ℹ️ _[Please read the following community guidelines ](https://discourse.mozilla.org/t/discussion-of-new-guidelines-for-recording-validation/36465)to know how to produce better voice donations_.

⚠️ _Note: Once you have recorded a decent amount of clips in your language (around 300), it’s more valuable for less effort if you jump into helping to get new voices from other people and focus on the voice validation part, this will increase the dataset quality._

#### **Voice validation**

The same site allows you to [review other people’s voices](https://voice.mozilla.org/listen) by listening to voices donated by the community. Each recording will need at least **two** positive validations from different people. Feel free to create an account to track your progress, compare with other contributors, set yourself goals or get awards badges.

<p style="text-align: right">
ℹ️ <em><a href="https://discourse.mozilla.org/t/discussion-of-new-guidelines-for-recording-validation/36465">Please read the following community guidelines </a>to know how to better validate voices</em>.</p>

#### **Community mobilization**

You can help the community by organizing activities and encouraging others to do the same. Use the channels we have at our disposal to engage with other contributors in your language, talk about your ideas to grow the community and collect and validate more voices.

ℹ️ _Check a few ideas from the [Contribute to Common Voice activity](https://community.mozilla.org/activities/contributing-to-common-voice/)._

⭐️ _You can re-use any [graphical material](https://drive.google.com/drive/u/0/folders/1RfgsCI6-rs1crh7OhlxryXO5-zN8JRErhttps://drive.google.com/drive/u/0/folders/1RfgsCI6-rs1crh7OhlxryXO5-zN8JRErhttps://drive.google.com/drive/u/0/folders/1RfgsCI6-rs1crh7OhlxryXO5-zN8JREr) we have produced to support the project._

#### **Community support**

Help other contributors in [our discourse](https://discourse.mozilla.org/c/voice/239) and [matrix](https://chat.mozilla.org/#/room/#common-voice:mozilla.org) channels. Answering their questions about how to use the site or helping document reported issues [on github](https://github.com/mozilla/voice-web/issues).

#### **Tooling development**

The main [development of our site](https://github.com/mozilla/voice-web/) is led by our staff team, but anyone can submit pull requests based on open issues, or minor UI bugs.

ℹ️ _[Please read the contribution guidelines](https://github.com/mozilla/voice-web/blob/master/CONTRIBUTING.md) before submitting any code_.


#### **Dataset releases**

The complete text and voice dataset for languages where we have data is currently generated by the Common Voice staff team.

Currently, we are generating a new version of the datasets two times per year and publishing them [on our site](https://voice.mozilla.org/datasets).

ℹ️ _Note that we are asking for an email to send the link to the dataset (instead of direct download) because we want to have a way to contact everyone who downloaded the data in case we get deletion requests from contributors._

We understand that some people might want more frequent releases, and we are working on a more continuous release model to accommodate these needs.

### Roles

These are some roles you can take as part of this community.

* Voice donator: Donate your voice.
* Voice validator: Help review other people’s voices.
* Support: Join our community channels to support contributors with issues using our site.
* Mobilizer: Help people in the community to get started and keep contributing.
* Developer: Help submitting code and fixes to our site.

### Channels

* [Common Voice discourse](https://discourse.mozilla.org/c/voice/) category.
* [Common Voice matrix](https://chat.mozilla.org/#/room/#common-voice:mozilla.org) chat room.
* [Common Voice project announcements](https://discourse.mozilla.org/tags/c/voice/announcements).

💬 If your language already exists on Common Voice, make sure you [check and join the local discourse](https://voice.mozilla.org/about#get-involved) and matrix room. If that’s not the case, please create a new topic [on discourse](https://discourse.mozilla.org/c/voice/239) asking for one to be created.

## 🌍 Localization

### Our purpose

Adapting the project tools and material to be understood by a specific audience.

### Who we are

We are a community of translators and linguists that localize the original English content into our languages.

🔨 _English knowledge and deep understanding of our local language and culture are key for this work._

### What’s success

Localize the project tools into our language, mainly the [Common Voice site](http://voice.mozilla.org/).

* The Common Voice site is 100% localized in my language.

### How to join

Anyone can join this community. Join our [discourse forums](https://discourse.mozilla.org/c/voice/) or our [matrix chat](https://chat.mozilla.org/#/room/#common-voice:mozilla.org) and introduce yourself, jump into our localization tool and check the status of your language.

### What we do

#### **Localization**

We use Mozilla’s localization tool, Pontoon, to translate the Common Voice strings. Please create an account and check your language on [Common Voice Pontoon section](https://pontoon.mozilla.org/projects/common-voice/).

ℹ️ _Please read [how to use pontoon](https://mozilla-l10n.github.io/localizer-documentation/tools/pontoon/) before starting to use the tool, you might need to ask the Mozilla localization team for permissions to validate suggestions_.

🔨 _Skills required to help: English knowledge, strong knowledge of your language._

### Roles

These are some roles you can take as part of this community.

* Localizer: Suggest new translations for the pending strings
* Reviewer: Check and validate existing suggestions and improve their quality.
* Mobilizer: Help people in the community to get started and keep contributing.

### Channels

* [Common Voice discourse](https://discourse.mozilla.org/c/voice/) category.
* [Common Voice matrix](https://chat.mozilla.org/#/room/#common-voice:mozilla.org) chat room.
* [Mozilla Localization matrix](https://chat.mozilla.org/#/room/#l10n-community:mozilla.org) chat room.
* [Common Voice project announcements](https://discourse.mozilla.org/tags/c/voice/announcements).

💬 If your language already exists on Common Voice, make sure you [check and join the local discourse](https://voice.mozilla.org/about#get-involved) and matrix room. If that’s not the case, please create a new topic [on discourse](https://discourse.mozilla.org/c/voice/239) asking for one to be created.
