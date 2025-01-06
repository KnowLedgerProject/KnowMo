# KnowMo
**KnowLedger** ecosystem repository for UI **module** development

The focus of this repository is the definition of a specification for modules, utilized in the KnowLedger Research Data 
Management (RDM) System.  Modules are generic containers for external resources (data repositories, services, tools, or 
any other resource useful for research) that researchers can integrate into their instance of KnowLedger.

The development team (request to join the team [here](https://github.com/KnowLedgerProject/KnowMo/issues/new?template=request-to-join.md))
is focused on defining the structure of the metadata for the definition of a module created for KnowLedger.  This is an
iterative process, and we plan to have multiple versions of the specification as other features and the core KnowLedger 
software evolve.

The general development stages are expected to be as follows:

1. core definition elements to define a module
2. module type specific metadata
3. instance metadata fields
4. event metadata needs (in the KnowLedger software)
5. semantic annotation definition
6. authentication layer metadata

A schema for the metadata development will be created in the JSON schema language.  Subsequently, a JSON-LD context file
will be developed to add the semantic annotation of module metadata fields.

Once the specification is developed enough, documentation will be developed on how to create instance JSON-LD to define 
instances of modules.  This will be used to gather use case issues/needs and eventually developed a set of unit tests 
for modules.
