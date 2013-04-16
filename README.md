state-of-the-art_Internship
===========================
Graphical DSMLs (Domain Specific Modeling Languages) are an alternative to general purpose
modeling languages e.g. UML or SysML. The objective of this languages is to describe
models with concepts and relations specific to a domain. Defining such languages consist of
defining an abstract syntax, a graphical concrete syntax and a correspondence between the
elements of each syntax. Such description form the language grammar. The process of defining
a grammar is composed of two phases : abstract syntax definition (1) and concrete syntax
definition (2). The abstract syntax is represented by a MOF 1.4 conforming meta-model and
the concrete one is derived from the abstract syntax by a transformation targeting a generic
meta-model of the graphical concrete syntax (Diagraph). Designing the concrete syntax implies
the definition of this transformation, the latter is registered into the abstract syntax trough
meta-data (annotations). In order to facilitate the concrete syntax conception, we aim to semiautomatize
the generation of this transformation, by operating a pattern mining process on the
abstract syntax meta-model.