# Introduction
Keyfile Corporation was one of the companies back in the 1990's that sold document management software. They are long defunct, but their website is available on wayback.org ([http://www.keyfile.com](https://web.archive.org/web/20180806111914/http://keyfile.com/)). One of the things they sold was:

> Keyfile Document Management and Workflow Software lets you handle many different forms of information: paper, fax, e-mail, word processor files, scanned photographs -- even voice and video -- more efficiently and cost effectively. Create workflows that determine -- and monitor in real time -- how documents are created, updated, reviewed and used.

A number of companies bought in back in the day, and glibly digitized millions of paper documents with the Keyfile software. All of these pages were stored in a proprietary flat file database, and as long as you had their software, it was a fairly decent system. 

20+ years later, we've got problems. The company doesn't exist anymore. There haven't been new versions of the software for years. The existing software is not supported on any current OS. The data stored in their proprietary database is only accessible through their software which has to be carefully maintained by knowledgeable IT staff on ancient versions of Windows that are also no longer supported.

This project is a customer-specific reverse engineering of the Keyfile database. The ruby code published here understands the keyfile binary data and can decode/extract documents from it. It's not perfect, but it was used to successfully extract ~2.5M pages of data for one entity, and the code is offered here under the GPL as a base from which to work, should anyone else have a need.
