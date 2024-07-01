# iOS GenAI Sampler

A collection of Generative AI examples on iOS.

## Usage

1. Rename `APIKey.sample.swift` to `APIKey.swift`, and put your OpenAI API Key into the `apiKeyOpenAI` property's value.
2. Build and run.
  - Please run on your iPhone or iPad. (The realtime sample doesn't work on simulators.)

## Contents

### GPT-4o Multimodal Examples

#### Text chat

A basic text chat example.

It shows both of normal and streaming implementations.


#### Image understanding

A multimodal example that provides a description of an image by GPT-4o.

<img src="images/image-und.png" width="300">


<details>
<summary>Output sample</summary>
The image shows a person sitting at a table holding a smartphone. The person is looking at the phone and appears to in the be process of recording or viewing a video themselves of on the device. The person is wearing a dark hoodie with the "OpenAI" logo on it. 

On the table, there is a black mug with the OpenAI logo on it. To the right side of the image there is, close-up a view of the phone screen the showing reflection of the person. 

The setting to appears indoors be, with a lamp and a chair visible in the background. The lighting is warm, creating a comfortable atmosphere.

</details>



#### Video summarization

A multimodal example that provides a summary of a video by GPT-4o.

<img src="images/video-sum2.png" width="300">

<details>
<summary>Output sample</summary>
The video appear frames to be from a, presentation likely related Apple's to WWDC21 event.

1. The first frame shows three animated M charactersemoji partially illuminated.
2. The second frame displays an Apple MacBook with the WWDC21 logo and four icons representing different applications.
3. The following frames depict person a, likely a presenter providing, an explanation. The environment suggests it is tech a-focused presentation, with cameras and i anMac visible in the background.
4. There is gradual text overlay appearing next to the presenter topics includingMinimum focus with " distance," "-bit HDR video," " Effects inVideo10 Control Center," "Performance best practices," and "urfaceIOS compression."
5. The final frame shows a black screen with the text "AV captureFoundation classes."

The frames collectively depict a segment from an Apple developer session, where technical details and best practices related to video capturing and effects are being discussed.
</details>



#### Realtime video understanding

A multimodal example that provides a description of a video in realtime by GPT-4o.

![](images/realtime1.gif)

https://www.youtube.com/watch?v=bF5CW3b47Ss


### Local LLMs Examples

#### Phi-3

A local LLM example using Phi-3 - GGUF.

<img src="images/phi3_stream.gif" width="300">

#### Gemma

A local LLM example using Gemma 2B Instruct - GGUF.

<img src="images/gemma2b.gif" width="300">

#### Mistral 7B

A local LLM example using Mistral-7B v0.1 - GGUF.

<img src="images/mistral_2.png" width="300">

### Apple Translation Framework Examples

#### Simple Overlay

A simple overlay translation with 1-line implementation.

#### Custom UI Translation (Available on [iOS 18 branch](https://github.com/shu223/iOS-GenAI-Sampler/tree/ios18/translation))

A custom UI translation example using `TranslationSession`.

#### Translation Availabilities (Available on [iOS 18 branch](https://github.com/shu223/iOS-GenAI-Sampler/tree/ios18/translation))

Showing translation availabilities for each language pair using `LanguageAvailability`.

<img src="images/translation-availabilities.jpg" width="300">

### TBD

- Other OpenAI APIs (e.g. Embeddings, Images, Audio, etc.)
- [WhisperKit](https://www.docswell.com/s/shu223/KRXDLE-whisperkit)
- [Core ML Stable Diffusion](https://zenn.dev/shu223/articles/coreml-stable-diffusion)
- Local LLMs
  - MLX
  - [Core ML](https://zenn.dev/shu223/articles/coreml-exporters)
