# AI Performance Playground - Sonar+D Hacklab Resources (2025)

Inspired by and adapted from the [Timbre Resources webpage](https://github.com/comma-lab/timbre-resources), this is a living document of resources to support the development of hacks & prototypes for the [AI Performance Playground organised by Sónar+D 2025](https://sonar.es/en/programme/sonar-d/open-call-hacklab) with the goal of exploring and deepening the use of machine learning tools, AI, and other related technologies with a critical perspective. Some of the tools have been mentioned by the Hacklab participants as part of their arsenal. The resources mainly focus on sound with a section related to visuals. Collaboratively and through the exchange of skills and knowledge, the aim of the Hacklab is to learn collectively to critically apply new tools in musical and performative practices, and what surrounds them. 

## User-friendly systems

[Audiostellar](https://audiostellar.xyz) | AI-powered experimental sampler

[Wekinator](http://www.wekinator.org) | Machine learning for building new musical instruments, gestural game controllers, computer vision or computer listening systems, among others.

[Stable Audio SPA](https://stableaudio.com) | a web app that generates 3 minute songs in 10 seconds.

[diffusion.cam](https://www.diffusion.cam) | an artificial social network that allows you to use the camera to transform your photograph into text, which gets turned back into an image using an AI diffusion model: img2text2img.

## Plug-ins

[Concatenator](https://datamindaudio.ai/concatenator-v1/) (DataMind Audio) | AI-powered audio mosaicing plug-in.

[Morpho](https://neutone.ai/morpho) (Neutone) | a realtime tone morphing plugin powered by advanced machine learning technology.  

[Dicy2](https://forum.ircam.fr/projects/detail/dicy2/) |  a package for Max and a plugin for Ableton Live implementing interactive agents using machine-learning to generate musical sequences that can be integrated into musical situations.

[Pitchshop](https://www.rullyshabara.id/pitchstop) | upload your own sound file and let the machine clone and manipulate the pitch.

## Machine learning and AI

[SP-Tools](https://rodrigoconstanzo.com/sp-tools/) | A set of machine learning tools that are optimised for low latency and real-time performance. The tools can be used with [Sensory Percussion sensors](http://sunhou.se/), ordinary drum triggers, or any audio input.

[FluCoMa](https://www.flucoma.org/) | The FluCoMa software consists of objects for decomposing and describing audio, and for manipulating collections of sonic data by querying, matching, learning and transforming. The complete toolkit is available for Max, SuperCollider and Pure Data, and the decomposition / description tools are available for the command line.

## Generative AI

[Stable Audio Open](https://stability.ai/news/introducing-stable-audio-open) | an open source text-to-audio model optimised for generating short audio samples, sound effects and production elements using text prompts.

[MusicFX DJ](https://labs.google/musicfx) (Google) | an extension of Google Music FX, a generative AI tool. In DJ Mode, you can create constantly evolving and generative soundscapes by inputting text prompts.

### Generative AI - Models

Stable Audio Open model available on [huggingface](https://huggingface.co/stabilityai/stable-audio-open-1.0).

[Stable Audio Tools](https://github.com/Stability-AI/stable-audio-tools) | Generative models for conditional audio generation.

## Neural sound synthesis

[nn~](https://acids-ircam.github.io/nn_tilde/) | At its core, nn~ is a translation layer between Max/MSP or PureData and the [libtorch c++ interface for deep learning](https://pytorch.org/). Alone, nn~ is like an empty shell, and requires pretrained models to operate. 

[neutone.space](https://neutone.space/) | A platform where researchers can share real-time AI audio processing models for creators to experiment with transformative AI audio instruments.

[vschaos2](https://github.com/acids-ircam/vschaos2) | a vintage neural audio synthesis package.

### Neural sound synthesis - Models

You can find a few [RAVE](https://github.com/acids-ircam/rave) models [here](https://acids-ircam.github.io/rave_models_download).

[Shuoyang Zheng/Jasper's RAVE models](https://huggingface.co/shuoyang-zheng/jaspers-rave-models).

You can find a few [vschaos2](https://github.com/acids-ircam/vschaos2) models [here](https://www.dropbox.com/sh/avdeiza7c6bn2of/AAAGZsnRo9ZVMa0iFhouCBL-a?dl=0).

## Livecoding

[Brunzit](https://github.com/g-roma/Brunzit) | a C++ application for experimenting with flocks of sonic agents through live coding where agents traverse a data terrain, a 2D visualization which can be created from a grey scale image or an audio file.

[Mob](https://github.com/g-roma/Mob) | a SuperCollider program that allows you to live-code a group of agents animated in a 2D surface, where each agent controls a synth. 

[Fuzz](https://github.com/tidalcycles/tidal-fuzz-completer) | Autocoder agent producing Tidal patterns and atom-auto suggestion package.

[MIRLCa](https://github.com/axambo/MIRLCa) | A set of SuperCollider extensions for live coding using MIR and machine learning.

## Datasets

[SOL](https://forum.ircam.fr/collections/detail/sol-instrumental-sounds-datasets/) | Ircam instrumental sound database coming from the Studio On Line project.

[Nsynth](https://magenta.tensorflow.org/datasets/nsynth) | 305,979 musical notes, each with a unique pitch, timbre, and envelope.

[Freesound](https://freesound.org/) | a collaborative collection of 618,244 free sounds.

[OpenMIC-2018](https://zenodo.org/records/1432913#.W6dPeJNKjOR) | 20000 audio clips with annotations of the presence or absence of 20 instrument classes.

[URMP](http://labsites.rochester.edu/air/projects/URMP.html) | 44 pieces of orchestral recordings with note-level and frame-level annotations.

[MIS](https://theremin.music.uiowa.edu/MIS.html) | single instrument notes with different playing techniques.

[Medley-solos-DB](https://zenodo.org/records/2582103) | an instrument recognition dataset, audio extracted from MedleyDB and solosDB.

[ISMIR Datasets](https://www.ismir.net/resources/datasets/) 

## Hardware

Using nn~ for PureData, RAVE can be used in realtime on embedded platforms, such as Bela or Raspberry Pi 4.

## Other software, platforms, resources (miscellaneous)

[Hugging Face](https://huggingface.co) | a resourceful collaborative platform with models, datasets, and applications.

[Cursor](https://www.cursor.com) | AI code editor.

[MIMIC](https://mimicproject.com) | a creative coding platform (courses, tutorials, code...) ranging from graphics, music, machine learning and stuff from Tensorflow.JS.

* MIMIC examples:
  * [Classification](https://mimicproject.com/code/6dfd19a3-ce91-c16f-b251-3f87e3c78e2f) - pose as input, controlling a classifier
  * [Regression](https://mimicproject.com/code/98d88675-bf57-3f21-02fd-90111394cb24) - Pose as input, controlling audio parameters using regression

## Visual (miscellaneous)

[Stable Diffusion](https://github.com/Stability-AI/generative-models) | a deep learning, text-to-image model based on diffusion techniques.

[Figma AI](https://www.figma.com/ai/) | a visualisation tool for idea representation.

[ComfyUI](https://www.comfy.org) | generate video, images, 3D, audio with AI.

[Luma AI](https://www.luma.ai) | software enabling the creation of realistic 3D images, videos, and game assets using iPhone or web.

[Luma AI API](https://docs.lumalabs.ai/docs/api) | Luma has made its NeRF and meshing models accessible via their API, offering developers advanced 3D modeling.

## Readings and talks

[Book] Nao Tokui (2023) ["Surfing human creativity with AI — A user’s guide"](https://naotokui.net/works/surfing-human-creativity-with-ai-a-users-guide/)

[Talk] Lauren Klein (April 24, 2024) ["Data Feminism for AI"](https://youtu.be/p9vbNA5_t44) (1:16:07)

[Article] Lauren Klein, Catherine D'Ignazio (2024) ["Data Feminism for AI"](https://facctconference.org/static/papers24/facct24-7.pdf) (FAccT ’24, June 03–06, 2024, Rio de Janeiro, Brazil). DOI: https://doi.org/10.1145/3630106.3658543

[Article] Fabio Morreale (2021) [Where Does the Buck Stop? Ethical and Political Issues with AI in Music Creation](https://transactions.ismir.net/articles/86/files/submission/proof/86-1-2717-1-10-20210720.pdf). Transactions of the International Society for Music Information Retrieval, 4(1), pp. 105–113. DOI: https://doi.org/10.5334/tismir.86

[Article] Karolina Jawad and Anna Xambó (2023) [Feminist HCI and narratives of design semantics in DIY music hardware](https://www.frontiersin.org/journals/communication/articles/10.3389/fcomm.2023.1345124/full). Frontiers in Communication, Volume 8 - 2023. DOI: https://doi.org/10.3389/fcomm.2023.1345124

## Performances

[Raw-Green-Rust perform Regulatory Capture by Owen Green | Dialogues Festival, Edinburgh College of Art, on the 7th of July 2021](https://youtu.be/8I7Nsjtvvyg)

[Alice Eldrige + Chris Kiefer: Feedback Cell plays FeedbackFeedforward | Dialogues Festival, Edinburgh College of Art, on the 9th of July 2021](https://youtu.be/c03_84_P7PQ)

[Owen Green: Race to the Bottom | Huddersfield Contemporary Music Festival, on the 21st of November 2019](https://youtu.be/zeOm9w3ZJVc)

[Lauren Sarah Hayes: Moon via Spirit | Huddersfield Contemporary Music Festival, on the 21st of November 2019](https://youtu.be/BzSRs_7S9cg)

[Rodrigo Constanzo: Kaizo Snare | Huddersfield Contemporary Music Festival, on the 21st of November 2019](https://youtu.be/MTWklm1oXWQ)

[Leafcutter John: Line Crossing | Huddersfield Contemporary Music Festival, on the 21st of November 2019](https://youtu.be/hYaZq1JCTQo)

[Gerard Roma: Big fry-up | Dialogues Festival, Edinburgh College of Art, on the 7th of July 202](https://youtu.be/MV4_S2fUyEY)

[AI and Music - Holly Herndon presents Holly+ feat. Maria Arnal, Tarta Relena and Matthew Dryhurst](https://youtu.be/Wk6T2WmhuJw)

[Jennifer Walshe: A Late Anthology Live | LIVE +RAIN Film Festival 2023](https://youtu.be/q_lknRtHWvQ)

[Nao Tokui: Emergent Rhythm | LIVE +RAIN Film Festival 2023](https://youtu.be/z6z4lXnDJ18)

[Albert Barqué-Duran: Slowly fading into data | LIVE +RAIN Film Festival 2023](https://youtu.be/Sjxej5ypzOc)

[Anna Xambó: Ceci n'est pas une usine | LIVE +RAIN Film Festival 2023](https://youtu.be/IQHcSbkJK5k)

[Nicholas Evans, Alba González, i Pablo Gorostiaga: Finding Light in the Distortion (MTG-UPF) | LIVE +RAIN Film Festival 2023](https://youtu.be/Q2f2PGTLDXo)

[Performing Critical AI I: Feedback Cell featuring Ollie Bown | Cafe Oto, London
November 27, 2022](https://youtu.be/UE2FqFqsm8Y?list=PL2aeDefey_GZNZ7jRnbKOI72Fu_KwDqoC)

[Performing Critical AI I: 4 Boxes at Cafe OTO (Anna Xambó) | Cafe Oto, London
November 27, 2022](https://youtu.be/eGSjD-K3bg4?list=PL2aeDefey_GZNZ7jRnbKOI72Fu_KwDqoC)

[Performing Critical AI I: Improvisation with/against Machine Learners (Owen Green, Pierre Alexandre Tremblay) | Cafe Oto, London
November 27, 2022](https://youtu.be/rMH-H1OuDqs?list=PL2aeDefey_GZNZ7jRnbKOI72Fu_KwDqoC)


