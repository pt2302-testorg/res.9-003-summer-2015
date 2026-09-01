---
content_type: page
description: This page presents a video-based tutorial on using the Church programming
  language.
draft: false
is_media_gallery: true
learning_resource_types:
- Tutorials
license: https://creativecommons.org/licenses/by-nc-sa/4.0/
ocw_type: SupplementalResourceSection
parent_title: Tutorials
parent_type: SupplementalResourceSection
parent_uid: 1991b27f-a447-8dc0-a6a2-79748088784f
title: 'Tutorial 5: Church Programming'
uid: 32907aca-b7d5-1972-49b3-b36fb769ce08
video_metadata:
  youtube_id: null
videos:
  content:
  - 3953a4fd-a909-910d-c0f2-697c6200da75
  - 1af5546c-cd66-7684-1fc9-19a46a77ff9b
  website: res-9-003-brains-minds-and-machines-summer-course-summer-2015
---
## Tutorial Overview

{{< tableopen >}}{{< tbodyopen >}}{{< tropen >}}{{< tdopen >}}
{{< resource uuid="20b84384-fbe1-fff3-7d7e-31991157e720" >}}
{{< tdclose >}}{{< tdopen >}}
Josh Tenenbaum and colleagues propose that our intuitions about properties like the stability of a stack of blocks, may derive from "probabilistic programs" that can simulate, with some uncertainty, the physics that governs how objects behave in space and time. Such programs can be implemented and tested using probabilistic programming languages such as the Church language. (Image courtesy of Josh Tenenbaum, used with permission.)
{{< tdclose >}}{{< trclose >}}{{< tbodyclose >}}{{< tableclose >}}

The unit on modeling human cognition introduced a framework based on the creation of generative models of the physical and social worlds that enable probabilistic inference about objects, agents, and events. The Church programming language was designed to facilitate the implementation and testing of such models. In this tutorial, you will first learn the syntax and some basic primitives of the Church language, and how to define functions that implement simple probabilistic models and inference methods. The concepts are then explored through examples such as hypothesis testing in the domain of coin-flipping, and reasoning about the goals and beliefs of an agent.

## Unit Activities

### Useful Background

- Introductions to probability and probabilistic approaches to modeling behavior
- {{% resource_link "855d4e86-2ca9-e529-74f0-cdef3de9e9c0" "Video lectures" %}} on computational models of cognition by Josh Tenenbaum
- Introduction to computer programming

### Videos and Slides

{{< video-gallery "32907aca-b7d5-1972-49b3-b36fb769ce08" >}}

### Code

{{% resource_link "3a08df29-46c9-1378-cf03-d672fec3e037" "Church\_examples (RTF)" %}} contains the code examples described in the two-part tutorial video. These examples can be executed by copying the code into one of the following Church programming environments. Code can also be written from scratch and modified in these environments:

1. First edition of the {{% resource_link "665f8e09-a3b3-430b-b51c-932e4d59b90d" "Probabilistic Models of Cognition" %}} electronic text, cited in the section below on *Future Study*, which includes a separate {{% resource_link "58cc9c7f-df36-44e0-9dde-f48476782a24" "Play space" %}} where code can be copied, modified, and executed
2. {{% resource_link "c24570dc-0a53-48c7-95cf-22c89f14b6c5" "webchurch engine" %}} that runs Church code in a web browser, which is available on GitHub for download onto your local computer

### Further Study

Goodman, N. D., and J. B. Tenenbaum. {{% resource_link "665f8e09-a3b3-430b-b51c-932e4d59b90d" "*Probabilistic Models of Cognition, First Edition*" %}} (electronic).

- This interactive text introduces many probabilistic modeling techniques and contains an embedded Church programming environment with coding examples throughout the text that can be modified and executed in place. The text also includes a separate {{% resource_link "58cc9c7f-df36-44e0-9dde-f48476782a24" "Play space" %}} and {{% resource_link "5cb5c329-521b-467c-bf25-127542a696e6" "Church language reference" %}}.

Goodman, N. D, and J. B. Tenenbaum. {{% resource_link "933d6df5-ccdc-444f-bded-bc1df90437b8" "*Probabilistic Models of Cognition, Second Edition*" %}} (electronic). With programming exercises written in the web-based probabilistic programming language, {{% resource_link "fd7a8c82-9dae-4552-b8be-ad04e47302e6" "WebPPL" %}}.

Goodman, N. D., and A. Stuhlmüller. {{% resource_link "c25dbfb3-4734-46d8-98ce-04011eb927ae" "*The Design and Implementation of Probabilistic Programming Languages*" %}}. (electronic)

- This online text describes how probablistic programming languages (PPLs) can be embedded in other languages, and introduces the {{% resource_link "c8c4c4c2-d841-4487-bd88-0492b6a5a890" "WebPPL" %}} language, a web-based PPL embedded in JavaScript.

{{% resource_link "ccdcb4a4-269f-454c-a7a3-adfbd4db663c" "forestdb.org" %}}: A repository of probabilistic models implemented in the Church language

The Church language is one of several probabilistic programming languages. Learn more about such languages at the {{% resource_link "9b0ff2dd-99ad-4609-bde0-e516ea7fed5b" "Probabilistic-Programming wiki" %}}.