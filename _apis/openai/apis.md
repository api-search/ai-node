---
name: OpenAI
description: >-
  OpenAI is an AI research and deployment company. Our mission is to ensure that
  artificial general intelligence benefits all of humanity. Our mission is to
  ensure that artificial general intelligence—AI systems that are generally
  smarter than humans—benefits all of humanity. We are building safe and
  beneficial AGI, but will also consider our mission fulfilled if our work aids
  others to achieve this outcome.
url: https://raw.githubusercontent.com/api-search/ai/main/_apis/openai/apis.md
created: 2024/04/14
modified: 2024/04/14
specificationVersion: '0.16'
tags: []
apis:
  - name: OpenAI Assistants API
    description: >-
      The Assistants API allows you to build AI assistants within your own
      applications. An Assistant has instructions and can leverage models,
      tools, and knowledge to respond to user queries. The Assistants API
      currently supports three types of tools - Code Interpreter, Retrieval, and
      Function calling. In the future, we plan to release more OpenAI-built
      tools, and allow you to provide your own tools on our platform.
    tags:
      - Assistants
      - Attaching
      - File
      - Files
      - Instructions
      - Models
      - Modifies
      - Returns
    properties:
      - type: Documentation
        url: https://platform.openai.com/docs/assistants/overview
      - type: OpenAPI
        url: properties/assistants-openapi-original.yml
    overlays:
      - type: APIs.io Search
        url: >-
          overlays/https://github.com/apis-json/artisanal/tree/main/apis/openai/assistants-openapi-search.yml
      - type: APIs.io Search
        url: overlays/assistants-openapi-search.yml
      - type: API Evangelist Ratings
        url: overlays/assistants-openapi-api-evangelist-ratings.yml
    aid: openai:openai-assistants-api
    humanURL: https://platform.openai.com/docs/assistants/overview
    baseURL: https://api.openai.com
    score: 1329
  - name: OpenAI Audio API
    description: >-
      The Audio API provides two speech to text endpoints, transcriptions and
      translations, based on our state-of-the-art open source large-v2 Whisper
      model.
    tags:
      - Audio
      - English
      - Generates
      - Inputs
      - Languages
      - Speech
      - Text
      - Transcribes
      - Transcriptions
      - Translations
    properties:
      - type: Documentation
        url: https://platform.openai.com/docs/guides/text-to-speech
      - type: OpenAPI
        url: properties/audio-openapi-original.yml
    overlays:
      - type: APIs.io Search
        url: >-
          overlays/https://github.com/apis-json/artisanal/tree/main/apis/openai/audio-openapi-search.yml
      - type: APIs.io Search
        url: overlays/audio-openapi-search.yml
      - type: API Evangelist Ratings
        url: overlays/audio-openapi-api-evangelist-ratings.yml
    aid: openai:openai-audio-api
    baseURL: https://api.openai.com
    humanURL: https://platform.openai.com/docs/guides/text-to-speech
    score: 128
  - name: OpenAI Chat API
    description: >-
      Given a list of messages comprising a conversation, the model will return
      a response., providing an AI chat interface you can use to engage with
      users.
    tags:
      - Chat
      - Completions
      - Conversations
      - Creates
      - Given
      - Models
      - Responses
    properties:
      - type: Documentation
        url: https://platform.openai.com/docs/api-reference/chat
      - type: OpenAPI
        url: properties/chat-openapi-original.yml
    overlays:
      - type: APIs.io Search
        url: >-
          overlays/https://github.com/apis-json/artisanal/tree/main/apis/openai/chat-openapi-search.yml
      - type: APIs.io Search
        url: overlays/chat-openapi-search.yml
      - type: API Evangelist Ratings
        url: overlays/chat-openapi-api-evangelist-ratings.yml
    aid: openai:openai-chat-api
    baseURL: https://api.openai.com
    humanURL: https://platform.openai.com/docs/api-reference/chat
    score: 149
  - name: OpenAI Chat Completions API
    description: >-
      Chat models take a list of messages as input and return a model-generated
      message as output. Although the chat format is designed to make multi-turn
      conversations easy, it’s just as useful for single-turn tasks without any
      conversation.
    tags:
      - Chat
      - Completions
      - Conversations
      - Creates
      - Given
      - Models
      - Parameters
      - Prompts
      - Provided
      - Responses
    properties:
      - type: Documentation
        url: https://platform.openai.com/docs/api-reference/chat
      - type: OpenAPI
        url: properties/completions-openapi-original.yml
    overlays:
      - type: APIs.io Search
        url: >-
          overlays/https://github.com/apis-json/artisanal/tree/main/apis/openai/completions-openapi-search.yml
      - type: APIs.io Search
        url: overlays/completions-openapi-search.yml
      - type: API Evangelist Ratings
        url: overlays/completions-openapi-api-evangelist-ratings.yml
    aid: openai:openai-chat-completions-api
    baseURL: https://api.openai.com
    humanURL: https://platform.openai.com/docs/api-reference/chat
    score: 281
  - name: OpenAI Embeddings API
    description: >-
      Learn how to turn text into numbers, unlocking use cases like search.
      OpenAI’s text embeddings measure the relatedness of text strings.
    tags:
      - Creates
      - Embedding
      - Embeddings
      - Inputs
      - Representing
      - Text
      - Vectors
    properties:
      - type: Documentation
        url: https://platform.openai.com/docs/guides/embeddings
      - type: OpenAPI
        url: properties/embeddings-openapi-original.yml
    overlays:
      - type: APIs.io Search
        url: >-
          overlays/https://github.com/apis-json/artisanal/tree/main/apis/openai/embeddings-openapi-search.yml
      - type: APIs.io Search
        url: overlays/embeddings-openapi-search.yml
      - type: API Evangelist Ratings
        url: overlays/embeddings-openapi-api-evangelist-ratings.yml
    aid: openai:openai-embeddings-api
    baseURL: https://api.openai.com
    humanURL: https://platform.openai.com/docs/guides/embeddings
    score: 112
  - name: OpenAI Files API
    description: >-
      Files are used to upload documents that can be used with features like
      Assistants and Fine-tuning. Upload a file that can be used across various
      endpoints. The size of all the files uploaded by one organization can be
      up to 100 GB.
    tags:
      - About
      - Across
      - Assistants
      - Attaching
      - Belong
      - Content
      - Contents
      - Endpoints
      - File
      - Files
      - Fine
      - Increase
      - Individual
      - Information
      - Learn
      - Limits
      - MB
      - Maximum
      - Messages
      - Million
      - More
      - One
      - Organizations
      - Returns
      - Size
      - Specific
      - Specified
      - Storage
      - Supported
      - Supports
      - The
      - Threads
      - Tokens
      - Tools
      - Types
      - Up
      - Uploaded
      - Uploads
      - Used
      - Various
    properties:
      - type: Documentation
        url: https://platform.openai.com/docs/api-reference/files
      - type: OpenAPI
        url: properties/files-openapi-original.yml
    overlays:
      - type: APIs.io Search
        url: overlays/files-openapi-search.yml
      - type: API Evangelist Ratings
        url: overlays/files-openapi-api-evangelist-ratings.yml
    aid: openai:openai-files-api
    baseURL: https://api.openai.com
    humanURL: https://platform.openai.com/docs/api-reference/files
    score: 894
  - name: OpenAI Fine Tuning API
    description: >-
      Manage fine-tuning jobs to tailor a model to your specific training data.
      Creates a fine-tuning job which begins the process of creating a new model
      from a given dataset.Response includes details of the enqueued job
      including job status and the name of the fine-tuned models once complete.
    tags:
      - About
      - Begins
      - Cancel
      - Creates
      - Creating
      - Dataset Response
      - Details
      - Enqueued
      - Events
      - Fine
      - Fine Tune
      - Fine Tuned
      - Fine Tuning
      - Given
      - Immediately
      - Includes
      - Including
      - Info
      - Jobs
      - Models
      - More
      - Names
      - Organization's
      - Process
      - Status
      - The
      - Tuning
      - Your
    properties:
      - type: Documentation
        url: https://platform.openai.com/docs/guides/fine-tuning
      - type: OpenAPI
        url: properties/fine-tuning-openapi-original.yml
    overlays:
      - type: APIs.io Search
        url: overlays/fint-tuning-openapi-search.yml
      - type: API Evangelist Ratings
        url: overlays/fine-tuning-openapi-api-evangelist-ratings.yml
      - type: APIs.io Search
        url: overlays/fine-tuning-openapi-search.yml
    aid: openai:openai-fine-tuning-api
    baseURL: https://api.openai.com
    humanURL: https://platform.openai.com/docs/guides/fine-tuning
    score: 492
  - name: OpenAI Images API
    description: >-
      Learn how to generate or manipulate images with DALL·E in the API. The
      Images API provides three methods for interacting with images - creating
      images from scratch based on a text prompt, creating edited versions of
      images by having the model replace some areas of a pre-existing image,
      based on a new text prompt, Creating variations of an existing image.
    tags:
      - Creates
      - Edited
      - Edits
      - Extended
      - Generations
      - Given
      - Images
      - Original
      - Prompts
      - Variations
    properties:
      - type: Documentation
        url: https://platform.openai.com/docs/guides/images
      - type: OpenAPI
        url: properties/images-openapi-original.yml
    overlays:
      - type: APIs.io Search
        url: overlays/images-openapi-search.yml
      - type: API Evangelist Ratings
        url: overlays/images-openapi-api-evangelist-ratings.yml
    aid: openai:openai-images-api
    baseURL: https://api.openai.com
    humanURL: https://platform.openai.com/docs/guides/images
    score: 120
  - name: OpenAI Models API
    description: >-
      List and describe the various models available in the API. You can refer
      to the Models documentation to understand what models are available and
      the differences between them.
    tags:
      - About
      - Availability
      - Available
      - Basic
      - Currently
      - Fine Tuned
      - Information
      - Instances
      - Models
      - Organizations
      - Owners
      - Permissioning
      - Provides
      - Providing
      - Roles
    properties:
      - type: Documentation
        url: https://platform.openai.com/docs/models
      - type: OpenAPI
        url: properties/models-openapi-original.yml
    overlays:
      - type: APIs.io Search
        url: overlays/models-openapi-search.yml
      - type: API Evangelist Ratings
        url: overlays/models-openapi-api-evangelist-ratings.yml
    aid: openai:openai-models-api
    baseURL: https://api.openai.com
    humanURL: https://platform.openai.com/docs/models
    score: 201
  - name: OpenAI Threads API
    description: Create threads that assistants can interact with.
    tags:
      - Belonging
      - Calls
      - Cancel
      - Cancels
      - Completed
      - Endpoints
      - File
      - Files
      - Given
      - Is
      - Messages
      - Modifies
      - One
      - Outputs
      - Returns
      - Runs
      - Single
      - Steps
      - Submit
      - Submitted
      - The
      - They're
      - Threads
      - Tool
    properties:
      - type: Documentation
        url: >-
          https://platform.openai.com/docs/assistants/how-it-works/managing-threads-and-messages
      - type: OpenAPI
        url: properties/threads-openapi-original.yml
    overlays:
      - type: APIs.io Search
        url: overlays/threads-openapi-search.yml
      - type: API Evangelist Ratings
        url: overlays/threads-openapi-api-evangelist-ratings.yml
    aid: openai:openai-threads-api
    baseURL: https://api.openai.com
    humanURL: >-
      https://platform.openai.com/docs/assistants/how-it-works/managing-threads-and-messages
    score: 1861
maintainers:
  - FN: API Evangelist
    url: http://apievangelist.com
    email: info@apievangelist.com
aid: openai
score: 308
overlays:
  - type: API Evangelist Ratings
    url: /overlays/api-evangelist-ratings.yml
---