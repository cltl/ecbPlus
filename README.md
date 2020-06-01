# ecbPlus

The ECB+ corpus is an extension to the EventCorefBank (ECB, Bejan and Harabagiu, 2010). A newly added corpus component consists of 502 documents that belong to the 43 topics of the ECB but that describe different seminal events than those already captured in the ECB. All corpus texts were found through Google Search and were annotated with mentions of events and their times, locations, human and non-human participants as well as with within- and cross-document event and entity coreference information. The 2012 version of annotation of the ECB corpus (Lee et al., 2012) was used as a starting point for re-annotation of the ECB according to the ECB+ annotation guideline.
The major differences with respect to the 2012 version of annotation of the ECB are:

(a) five event components are annotated in text:

actions (annotation tags starting with ACTION and NEG)
times (annotation tags starting with TIME)
locations (annotation tags starting with LOC)
human participants (annotation tags starting with HUMAN)
non-human participants (annotation tags starting with NON_HUMAN)

(b) specific action classes and entity subtypes are distinguished for each of the five main event components resulting in a total tagset of 30 annotation tags based on ACE annotation guidelines (LDC 2008), TimeML (Pustejovsky et al., 2003 and Sauri et al., 2005)

(c) intra- and cross-document coreference relations between mentions of the five event components were established:
INTRA_DOC_COREF tag captures within document coreference chains that do not participate in cross-document relations; within document coreference was annotated by means of the CAT tool (Bartalesi et al., 2012)
CROSS_DOC_COREF tag indicates cross-document coreference relations created in the CROMER tool (Girardi et al., 2014); all coreference branches refer by means of relation target IDs to the so called TAG_DESCRIPTORS, pointing to human friendly instance names (assigned by coders) and also to instance_id-s
(d) events are annotated from an “event-centric” perspective, i.e. annotation tags are assigned depending on the role a mention plays in an event (for more information see ECB+ references).

CONTENTS

* 982 ECB+ corpus texts in the XML format: ECB+.zip
* ECB+ annotation guideline: NWR-2014-1.pdf
* Index of sentences annotated with coreference: ECBplus_coreference_sentences.csv (see README.TXT)
* LICENSEDATA.TXT
* COPYING-CC.TXT
* README.TXT.

When using this resource in publications please cite:

* Agata Cybulska and Piek Vossen. 2014. Using a sledgehammer to crack a nut? Lexical diversity and event coreference resolution. In Proceedings of the 9th international conference on Language Resources and Evaluation (LREC2014)
The ECB+ corpus is also described in:
* Agata Cybulska and Piek Vossen. 2014. Using a sledgehammer to crack a nut? Lexical diversity and event coreference resolution. In Proceedings of LREC 2014.
* Agata Cybulska and Piek Vossen. Guidelines for ECB+ Annotation of Events and their Coreference. 2014. (http://www.newsreader-project.eu/files/2013/01/NWR-2014-1.pdf)

Other relevant references:

* Linguistic Data Consortium. 2008. Ace (automatic content extraction) english annotation guidelines for entities, version 6.6 2008.06.13. Technical report, June. http://projects.ldc.upenn.edu/ace/docs/English-Entities-Guidelines v6.6.pdf.
* Bartalesi Lenzi, Valentina, Moretti, Giovanni, and Sprugnoli, Rachele. 2012. CAT: the CELCT Annotation Tool. In Proceedings of LREC 2012.
* Cosmin Bejan and Sanda Harabagiu. 2010. Unsupervised Event Coreference Resolution with Rich Linguistic Features. In Proceedings of ACL 2010, pages 1412–1422.
* Christian Girardi, Manuela Speranza, Rachele Sprugnoli and Sara Tonelli, 2014. CROMER: a Tool for Cross-Document Event and Entity Coreference. In Proceedings of the International Conference on Language Resources and Evaluation LREC 2014
* Heeyoung Lee, Marta Recasens, Angel Chang, Mihai Surdeanu and Dan Jurafsky. 2012. Joint Entity and Event Coreference Resolution across Documents. In Proceedings of EMNLP 2012
* Pustejovsky, James, Castano, Jose, Ingria, Bob, Sauri, Roser, Gaizauskas, Rob, Setzer, Andrea, and Katz, Graham. 2003. Timeml: Robust specification of event and temporal expressions in text. In Proceedings of Computational Semantics Workshop (IWCS-5)
* Saur´ı, Roser, Littman, Jessica, Knippen, Robert, Gaizauskas, Robert, Setzer, Andrea, and Pustejovsky, James. (2005). Timeml 1.2.1 annotation guidelines, October. http://timeml.org/site/publications/timeMLdocs/annguide 1.2.1.pdf.
