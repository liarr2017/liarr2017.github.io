---
layout: default
---

# Purpose

The purpose of this proposed workshop is to bring together the community of researchers using Lucene, and its derivatives like Solr and Elasticsearch, and develop tools for IR research. LIARR is not a traditional "mini conference"-style workshop with a call for papers, reviewed by a programme committee, and then presented. Rather it is a hackathon for attendees to actually work with Lucene in a hands-on capacity. Presentations are meant only as a tool for structuring and guiding the efforts of attendees. Hence, the workshop motto of: ***less yaking, more hacking***.

The goals of this workshop are to:
 - create a development plan and common codebase for IR research with Lucene,
 - implement various information retrieval methods in Lucene/Solr/Elasticsearch,
 - evaluate the quality of such methods and models.

The aim is to take state of the art in the IR field and provide prototype implementations, where we will focus on:

- exposing the standard functions that we need to have access to when we want to code up a retrieval model;
- getting some of the core retrieval functions in there;
- provide an understanding on how some of the functions are implemented in Lucene and how they deviate from how people know them in IR;
- provide a roadmap and set of guidelines to researchers and developers for which models/algorithms/techniques should the community include next into Lucene and how this should be done.

# Format

The workshop is a full day workshop and is organised as follows:

 - **Session One (morning):**: Introduction talks followed by pitches for ideas for teams to work on (ideas will also be collected through a pre-workshop online discussion). Scheduled introduction talks:
	- [Lucene4IR](https://www.github.com/leifos/lucene4ir) &mdash; Leif Azzopardi will explain the code base of the previous hackathon showing how to run a standard IR batch experiment and evaluate it, and then explain how to hack and mod the toolkit.
	- [Anserini](https://github.com/lintool/Anserini) &mdash; Jimmy Lin will give an overview of Anserini, which provides a range of applications for indexing and retrieval using Lucene.
 - **Session Two (morning):** Break up into teams to work on the different ideas. In parallel other breakout groups will provide training and explaining how the core works and how to mod/hack Lucene for the purpose of running TREC-style research experiments:
	- InnerLoop - Jake Mannix, from Lucidworks, will explain the inner loop of Lucene, describing how the scoring function works so that participants have a better understanding of how to develop their own methods.
	- Elastic4IR - Guido Zuccon will explain how Elasticsearch can be used for IR experimentation, outlining the point of departure between current retrieval methods in Elasticsearch and how these are instead defined and understood in IR.
 - **Session Three (afternoon):** Starting off with a quick report on progress before teams continue hacking.
 - **Session Four (afternoon):** Finalising and evaluating the methods implemented. Followed by a summary of progress from each of the teams and a plenary to discuss future directions of work and activities.

# Prizes

There will be a series of sponsored Prizes for various awards.

# Organizers

 - Leif Azzopardi (University of Strathclyde),
 - Grant Ingersoll (Lucidworks),
 - Jimmy Lin (University of Waterloo),
 - Yashar Moshfeghi (University of Glasgow), and
 - Guido Zuccon (Queensland University of Technology)
