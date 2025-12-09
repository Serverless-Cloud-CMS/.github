# Serverless CMS Organization
Welcome to the Serverless CMS Organization.  This was setup to support a book written 6 years ago about building Event Driven Architectures (EDA) for a Content Management System using AWS Serverless technology.  AWS was the initial approach, but this can be implemented in any CSP (Cloud Service Provider) that supports Serverless functions using messaging and event driven workflows.

The focus of this organization is the book, labs and building out a set of re-usable code bases to implment the books approach but go a step further.

* [Serverless CMS Book](https://github.com/Serverless-Cloud-CMS/serverless-cms-book)
* [Serverless CMS Book Labs](https://github.com/Serverless-Cloud-CMS/book-labs)

I decided to open source the book and labs since many of these ideas are well established now, and I wanted to freeze the work for the next step.  Though these concepts are all out on the web in some form as patterns or blogs, the book's depth is to show an actual implementation and cover many topics in DevOps to Application architecture using 12 Factor design concepts.  After my last position, I feel this book is more important than ever since developers have a phobia to distrubuted systems.  I hope the book shows doing these techniques really does make it clear and demonstrate that serverless technologies and event based architectures can help scale ideas safely and iteratively.

## Serverless CMS Book
The book walks you through mapping a traditional LAMP(Linux, Apache, MySQL and PHP) stack to a Serverless CMS architecture.  The goal is to demonstrate using Serverless technologies, containers and DevOps + configuration focused architecture can evolve supporting more and more features as a "plug and play" type prcoess.

## Book Labs
The labs are fully deployable and provide the general approach and could be used to spin up a fully working Blog site. The code is not necesarily production level and is not the focus of the book.  In fact, the goal is the reader can swap out there approach, such as writing a GoLang Tranformer instead of JavaScript.  JavaScript is common and most readers (especially Web Developers) can understand the code.  

## CMS Editor
The book labs have an embedded Editor which is a copy of the [cms-editor](https://github.com/Serverless-Cloud-CMS/cms-editor) in this organization that is stand alone. 

The cms-editor was developed using AI agents and other manual coding but as a base experiement with building out apps.  

The book labs commit trees are kept clean to allow the reader to compare Lab8 to Lab9 branches to see what was introduced and changed.  

## Book or Lab Issues
Please file a Issue ticket for any issues with the Book content or Labs.  
