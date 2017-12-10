## Chapter 1
<div style="text-align: justify">
This chapter covers the overall context for this book on the topic of software application localization (or app localization).
It surveys the main localization activities, which are separated into three categories.
The first category concerns the translation activities that can be effectively enhanced and supported by a myriad of translation tools (such as translation memory and machine translation).
These activities mostly focus on the translation of textual content, such as user interface strings and user assistance content.
The second category relates to non-translation activities, such as file processing and testing, which are necessary to glue the output of the translation activities into target files.
The third category, which is labelled as adaptation concerns activities that do not belong to the other two categories.
Adaptation activities include the localization of non-textual content, such as graphics or videos, and the translation of content that requires a very high level of transformation.
These activities are often supplemented with some upstream processes to prepare source content in globalization workflows.
This set of processes is often referred to as internationalization, especially in the IT industry, where software must ideally be internationalized before it gets localized.

## Chapter 2

Linguistic skills alone are not sufficient to be a good translator.
As far as software (application) localization is concerned in the Information and Communications Technology (ICT) sector, excellent technical skills are required.
These skills include both standard computing skills and automated text processing skills.
The objective of this chapter is to contribute towards the acquisition of some of these technical skills.
After an overview of the trends that are currently affecting the development of software applications (or apps), this chapter provides an introduction to software development methodologies (e.g. agile), programming languages, encodings (with a focus on Unicode), software strings and files (including TMX, XLIFF and PO) in order to equip the reader with the minimal technical knowledge required to feel at ease when working on the localization of an application's components.
The focus is on the Python programming language.
This chapter also introduces advanced text manipulation techniques using regular expressions, which can be extremely useful when dealing with large volumes of digital, textual files.





## Chapter 3

A software application is written using programming languages and mark-up languages.
However, only one natural language is often used for its interface and resources because software applications are often targeting a specific market.
When such a software application is initially designed, making it available in multiple languages for different markets may not be a priority or requirement.
When this is the case, the source code may not be prepared for future localization activities.
In other words, the source code is not internationalized.
When a program is not internationalized, it may still be possible to have it localized, but the localization process will be difficult and costly.
The first section of this chapter provides an overview of the various components of an application that may be subject to internationalization or localization activities (using as an example the Python-based Django framework).
This chapter presents some of the challenges that may arise when a non-internationalized software application is being localized, as well as a review of possible internationalization strategies.
Finally, the chapter reviews some of the internationalization techniques (such as content writing guidelines and controlled language rules) that can be applied to application-related content other than software strings.





## Chapter 4

With the advent of modern Web applications, the distinction between software strings, documentation content and information content is no longer clear-cut.
Modern localization processes try to abstract most of the complexity that was characteristic of large localization projects in the 1990s and 2000s.
Modern processes tend to rely on flexible workflows where content updates are handled continuously.
The steps of a traditional globalization workflow include the internationalized creation of source content, the extraction of this content into a format that can be easily translated into one or multiple target languages, the actual translation the content, the merging of the translated content back into the original file(s) and finally some post-processing (including quality assurance testing) to make sure that no problems were introduced during any of the previous steps.
This chapter focuses on all of the localization-related steps: extraction, translation, merging, building and testing, when applied to various content types pertaining to an application's ecosystem, including software content, user assistance and information content.
This chapter focuses on localization steps and processes (including content segmentation and reuse, and the use of translating guidelines) rather than on the translation technology tools that may be used to perform or support the actual translation task.


## Chapter 5

This chapter focuses on the technology that is linked to content translation from one language into another.
Translation management systems and translation environments provide most of the infrastructure required for the translation step in localization workflows.
Tools that are used to reuse previous translations and handle terminology during localization processes are also covered.
While terminology is at the core of most translation tasks, it is particularly crucial in the localization of Web and mobile applications, since users tend to interact with applications through translated strings.
This chapter also focuses on machine translation, which is used increasingly to support, enhance, and in some cases replace the translation step in localization workflows.
From a translation buyer and translator's perspective, it is therefore essential to know when and how this technology should be used.
After a section on post-editing, this chapter covers quality assurance tasks that are performed in localization workflows, especially during the translation process.
These tasks, which are performed by a range of stakeholders (translation buyers, language service providers, translators, translation revisers, in-country reviewers and translation users) rely on quality standards and models, which can be leveraged thanks to manual or automated checks (based on rules-based, statistics or machine-learning techniques).

## Chapter 6

A major goal in capturing and retaining an app user is to meet their expectations by identifying situations which require content to be adapted.
This chapter focuses on those adaptation scenarios that are related to non-textual content types, including images, audio and video.
Other adaptation situations may arise when the main element to keep from the source content is the intended impact on the target audience.
This chapter provides more detail on such adaptation processes (e.g. transcreation) and their implications for multilingual applications.
Besides, the traditional approach to content localization does not address the functional dimension of a given application.
Translators with advanced text processing or language engineering skills can play a fundamental role in defining adaptation requirements, especially if the application's functionality that requires adaptation is concerned with content processing.
Finally, the ability to provide multilingual applications that will not compromise the user experience regardless of the user's location should be considered.
In such a scenario, the system infrastructure that supports a given multilingual application must be architected in a user-aware manner so that content and services are located as close as possible to their user base in order to minimize slow response times (and frustration).





## Chapter 7
The global software industry, including the localization industry, is going through many changes, which makes it very different from what it was at the beginning of the 2000s (or even 2010s).
Some of these changes, such as continuous or in-context localization, are extremely disruptive and have a profound impact on the daily work of translators and localizers.
The topics covered in the previous chapters are revisited in the light of current and future trends, such as mobile and cloud computing.
Additional research opportunities are also identified.
The second part of this chapter attempts to be even more future-facing and briefly discuss some of the new directions that global application publishers could embrace in the years to come in order to understand the impact they may have on the world of translators.
While text is likely to remain a very important medium of communication in the foreseeable future, it is conceivable that other multimodal interactions will become popular as new computing devices and paradigms emerge.
For instance, spoken input is gaining in popularity thanks to the pervasiveness of mobile devices and applications that fulfil the role of personal assistants).
</div>
