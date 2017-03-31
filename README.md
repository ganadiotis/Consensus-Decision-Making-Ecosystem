<h2>Abstract</h2>

eDialogos Consensus is a standardised data schema (also referred as "ontology" or "vocabulary") designed to reflect the deliberation process in expert systems that obtain the final guidelines through participative role of domain specialists. 

The primary focus of the model is the process of reaching a consensus on certain issues through discussion of many different points of view. 

This document contains the description of the ontology and instructions on how to connect it with descriptions of other resources.

<h2>1 Introduction</h2>

This specification is a formal description of a metadata schema that can be applied to data of systems that allow deliberation over various topics and embed mechanisms to describe the process of reaching consensus. 

The goal of the this section is to provide the basic knowledge to comprehend the technical part of the specification. As such it shall introduce both Semantic Web and general topic of consensus representation and deliberation modelling.

The principal design goal of eDialogos Consensus is to reuse existing ontologies and link together in a new context a number of already defined key concepts for the deliberation process; please refer to ontology overview diagram to see how this goal has been achieved.

An important note is that eDialogos Consensus ontology presented here is not a complete model to address the problem of describing and linking deliberation activities in Web systems and inside enterprises. 

This schema defines concepts that are not described by other ontologies and provides the data attributes that enable to connect personal statements together and with contextual information already defined in metadata created with other ontologies.

<h3>1.1 Deliberation process and consensus modelling basics</h3>

Historically, the first approach to collaborative problem solving was the IBIS (Issue-Based Information System) methodology by Horst Rittel back in the 1960s. 

Inevitably all subsequent collaborative problem solving approaches somehow reference it. IBIS success lies in the fact that it provides a structure and a process simple to conceive. 

The basic model includes just a few concepts:
 Q: Question
       A: Alternative / Answer
          P: Pro
          C: Con
     
As the time progressed there have been a number of approaches to model discussions taking into account different goals and the changing reality of how people collaborate.

The eDialogos Consensus ontology is a solution for modelling discussions as interpreted by IBIS but in the context of the contemporary Web and taking into account the necessity to integrate different information systems with the use of Web technologies (and more specifically metadata publishing and light-weight information system integration). 

For a quick introduction to IBIS, please refer to this document: http://www.cognexus.org/IBIS-A_Tool_for_All_Reasons.pdf

Besides IBIS, the ontology heavily reuses concepts from GI2MO ( http://www.gi2mo.org/0.4/ns.html ), as the concept of Idea is key in this domain and is extended by the Position concept, and peripheral concepts are also reused to model the Collaborative Decision Making domain.

<h3>1.2 The Semantic Web</h3>

The Semantic Web is a W3C initiative that aims to introduce rich metadata to the current Web and provide machine readable and processable data as a supplement to human-readable Web.

Semantic Web is a mature domain that has been in research phase for many years and with the increasing amount of commercial interest and emerging products is starting to gain appreciation and popularity as one of the rising trends for the future Internet.

One of the corner stones of the Semantic Web is research on inter-linkable and interoperable data schemas for information published online. Those schemas are often referred to as ontologies or vocabularies. 

In order to facilitate the concept of ontologies that lead to a truly interoperable Web of Data, W3C has proposed a series of technologies such as RDF and OWL. 

eDialogos Consensus uses those technologies to enable publishing and processing of information related to deliberation process and in particular the building blocks of the achieved consensus by Web communities.

<h3>1.3 What is eDialogos Consensus for?</h3>

The goals of the eDialogos Consensus ontology to achieve as a data schema are:

-> enable to publish and consume raw data about discussions and how they lead to achieving a consensus

-> interconnect data from different collaborative deliberation platforms and allow for all of them to take part in the discussion process marking distinct impact on the consensus achievement

For more information please refer to http://www.imc.com.gr/ontologies/eDialogos/consensus/
