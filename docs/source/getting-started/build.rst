Build
===================

BentoML Overview 📖
-------------------

BentoML is an open-source platform that provides a streamlined solution to the challenges faced by teams in building and serving ML models. It supports work in an **Integrated Development Environment (IDE)** as well as in a flexible **Notebook** environment, ensuring a seamless model serving experience.

Its strength lies in its extensive **integration** with a wide range of AI frameworks, thus guaranteeing support for your AI models regardless of their complexity. To learn about the various frameworks that integrate with BentoML, visit `here <https://docs.bentoml.org/en/latest/frameworks/index.html>`_.

As BentoML is built with **Python 🐍**, it offers an intuitive coding experience for ML practitioners, seamlessly integrating with popular libraries within the Python ecosystem. This makes your coding experience both familiar and efficient.

BentoML embraces **open standards** for AI applications and promotes **best practices** to enhance the quality of your work. It offers a versatile framework capable of unifying **online**, **offline**, and **streaming** workloads.

In essence, BentoML aims to simplifies the process of building ML models, ensuring your team can focus on what truly matters: creating AI applications that solve real-world problem.

Building Your Bento 🍱
----------------------

Let's delve into how to **BUILD** a service with HuggingFace’s transformers.

Start by cloning the repository::

    git clone <https://github.com/bentoml/transformers-nlp-service.git>

Then, install the required dependencies::

    pip install -r requirements.txt

To serve your model as an HTTP server, utilize the ``bentoml serve`` CLI command. This starts a local server, making your model accessible as a web service.

Congratulations! You've just served your first model with BentoML. Visit `localhost:3000 <http://localhost:3000/>`_ to interact with your service. It's as straightforward as that!

Next, build your Bento::

    bentoml build

Your Bento is now ready! A Bento, in BentoML, is the unit of distribution. It packages your program's source code, models, files, artifacts, and dependencies. This Bento can be distributed and deployed across a variety of platforms.

To learn how to deploy your Bento with BentoCloud, check out the next article — :doc:`Getting Started -- SHIP <ship>`



----------------
Bento Gallery 🖼️
----------------

The Bento Gallery is a curated collection showcasing various types of ML models built and served using BentoML. Explore, learn, and draw inspiration from these showcased projects.

.. grid:: 2 3 3 3
    :gutter: 3
    :margin: 0
    :padding: 3 4 0 0

    .. grid-item-card:: Transformer
        :link: https://github.com/bentoml/transformers-nlp-service
        :link-type: url

        A modular, composable, and scalable solution for building NLP services with Transformers

    .. grid-item-card:: Pneumonia Detection
        :link: https://github.com/bentoml/Pneumonia-Detection-Demo
        :link-type: url

        Healthcare AI 🫁🔍 built with BentoML and fine-tuned Vision Transformer (ViT) model

    .. grid-item-card:: Fraud Detection
        :link: https://github.com/bentoml/Fraud-Detection-Model-Serving
        :link-type: url

        Online model serving with Fraud Detection model trained with XGBoost on IEEE-CIS dataset

    .. grid-item-card:: Optical Character Recognition (OCR)
        :link: https://github.com/bentoml/OCR-as-a-Service
        :link-type: url

        An efficient solution for converting PDFs into text 🚀

    .. grid-item-card:: CLIP
        :link: https://github.com/bentoml/CLIP-API-service
        :link-type: url

        Discover the effortless integration of OpenAI's innovative CLIP model with BentoML.

    .. grid-item-card:: OpenLLM
        :link: https://github.com/bentoml/OpenLLM
        :link-type: url

        Build, fine-tune, serve, and deploy Large-Language Models including popular ones 
        like StableLM, Llama, Dolly, Flan-T5, Vicuna, or even your custom LLMs.
