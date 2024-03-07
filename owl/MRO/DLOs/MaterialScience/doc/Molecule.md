# **MOLECULE**

**General Concept Info:**

| **IRI:**                 | *Molecule*                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
|--------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **OWL Type:**            | *Class*                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| **Concept Elucidation:** |  Molecule is a physical matter defined by an exact number of e-bonded atomic species and an electron cloud made of the shared electrons.  Comment: periodic entities like nanotubes are excluded   Comment: non-neutral entities are excluded.  Comment: one atom is not included.  Comment: the type of bond between constituents is defined as e-bonded, which is more precise than a definition stating “by attractive forces” and less exclusive than a definition based on potential energy.  Comment: The definition is not based on properties.  Comment: Molecule is one type of Molecular Entity. The last also includes periodic, non-neutral, single atom entities.  |
| **Labels:**              | *Labels used to address the concept, ordered as:* *preferred (one)*  Molecule (more than one atom)  *alternative (multiple)*  None                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |

**Knowledge Domain Resources:**

| **Related Domain Resources:** |   Schema.org  Not included  Wikipedia: A **molecule** is a group of two or more [atoms](about:blank) held together by [attractive forces](about:blank) known as [chemical bonds](about:blank); depending on context, the term may or may not include [ions](about:blank) which satisfy this criterion. In [quantum physics](about:blank), [organic chemistry](about:blank), and [biochemistry](about:blank), the distinction from ions is dropped and *molecule* is often used when referring to [polyatomic ions](about:blank).  2. Merriam-Webster: **T**he smallest particle of a substance that retains all the properties of the substance and is composed of one or more atoms.  3. Callister: No definition is given, only molecular chemistry and polymer molecular structure is.   4. Raabe:  No definition.   5. Wikidata: [molecule (Q11369)](about:blank)  electrically neutral entity consisting of more than one atom (n \> 1); rigorously, a molecule, in which n \> 1 must correspond to a depression on the potential energy surface that is deep enough to confine at least one vibrational state   6. IUPAC-Goldbook: An electrically neutral entity consisting of more than one atom (n\>1). Rigorously, a molecule, in which n\>1 must correspond to a depression on the potential energy surface that is deep enough to confine at least one vibrational state..   7. Britannica dictionary: **molecule**, a group of two or more [atoms](about:blank) that form the smallest identifiable unit into which a pure substance can be divided and still retain the [composition](about:blank) and chemical properties of that substance.  8 ISO Standards:  The singular term molecule is not defined in ISO Standards. Instead, particular molecules or roles that molecules have, or properties of molecules are defined. E.g.: linker molecule, reporter molecule, oligomer molecule.   9 IOF Core:  Molecule does not appear as a class and as term in other classes definition  10 MATPORTAL: see   |
|-------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Comments:**                 |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |

**Alignments To Existing Ontologies:** *(1: vertical, MLOs/TLOs; 2: horizontal, DLOs)*

**1: Vertical Alignments**

NA

**2: Horizontal Alignments**

**Nanomine**

| **Target Ontology:**           | *http://nanomine.tw.rpi.edu/ns*                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
|--------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Related Ontology Entities:** | Molecule(<http://semanticscience.org/resource/Molecule>)  Molecule is defined as “A molecule is a single chemical entity composed of fully covalently bonded atoms.” Molecule is a subclass of Chemical Entity  ((Chemical Entity(http://semanticscience.org/resource/ChemicalEntity)  defined as “A chemical entity is a material entity that pertains to chemistry.”  Chemical Entity is a subclass of Material entity  (Material Entity(http://semanticscience.org/resource/Molecule) defined as “A material entity is a physical entity that is spatially extended, exists as a whole at any point in time and has mass.” |
| **Mapping Elucidation:**       |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| **Semantic Relation Level:**   | Equivalent                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| **Mapping Axioms:**            |  *owl:equivalentClass*                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |

NPO: NanoParticle Ontology for Cancer Nanotechnology Research

| **Target Ontology:**           | *http://purl.bioontology.org/ontology/npo\#NPO_147*                                                                                                                                                                                         |
|--------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Related Ontology Entities:** | A molecule is a group of atoms bonded together, representing the smallest fundamental unit of a chemical compound that can take part in a chemical reaction.”  It is a subclass of Pure Substance (see discussion in BT Molecular Entity)   |
| **Mapping Elucidation:**       | *The elucidation is not very precise in its specification of the bonding between the atoms. The elucidation is hinging on a property (chemical).*                                                                                           |
| **Semantic Relation Level:**   | *Similarity (e.g. skos:related).*                                                                                                                                                                                                           |
| **Mapping Axioms:**            |                                                                                                                                                                                                                                             |

MSEO Material Science and Engineering Ontology

| **Target Ontology:**           | *https://purl.matolab.org/mseo/mid* |
|--------------------------------|-------------------------------------|
| **Related Ontology Entities:** | *Molecule is not defined.*          |

Materialsmine== Nanomine

| **Target Ontology:**           | *http://materialsmine.org/ns*                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
|--------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Related Ontology Entities:** | *Molecule(*[*http://semanticscience.org/resource/Molecule*](http://semanticscience.org/resource/Molecule)*)* *Molecule is defined as “A molecule is a single chemical entity composed of fully covalently bonded atoms.”*  *Product, isomer, substrate are subclasses of Molecule.*  *Molecule is a subclass of Chemical Entity that is defined as “A chemical entity is a material entity that pertains to chemistry.”*  *Chemical Entity(http://semanticscience.org/resource/ChemicalEntity)*  |
| **Mapping Elucidation:**       | *The elucidation hinges on a property (chemical) , but is otherwise similar.* *ONTOCOMMONS:molecules might not be chemical.*                                                                                                                                                                                                                                                                                                                                                                     |
| **Semantic Relation Level:**   |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| **Mapping Axioms:**            | MM:molecule SubClass of ONTOCOMMONS:molecule                                                                                                                                                                                                                                                                                                                                                                                                                                                     |

LPBFO==MSEO

| **Target Ontology:**           | *https://www.emi.fraunhofer.de/ontologies/LPBFO*                                                                                                                                      |
|--------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Related Ontology Entities:** | *LPBFO has the same taxonomy of MSEO but here there are references to concepts of the classes*   *Molecule is defined by* [*https://en.wikipedia.org/wiki/Molecule*](about:blank)*.*  |

CHEBI

| **Target Ontology:**           | [http://purl.obolibrary.org/obo/chebi](about:blank)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
|--------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Related Ontology Entities:** | *Molecule(*<http://purl.obolibrary.org/obo/CHEBI_25367>*)* *Molecule is defined as “*Any polyatomic entity that is an electrically neutral entity consisting of more than one atom*.”*  It is a subclass of Polyatomic Entity that is defined as “Any molecular entity consisting of more than one atom.” *PolyatomicEntity(*http://purl.obolibrary.org/obo/CHEBI_36357)  Polyatomic Entity is a subclass of Molecular entity, defined as “Any constitutionally or isotopically distinct atom, molecule, ion, ion pair, radical, radical ion, complex, conformer etc., identifiable as a separately distinguishable entity.” *MolecularEntity (*[http://purl.obolibrary.org/obo/CHEBI_23367](about:blank)*)*  Molecular Entity is a subclass of Chemical Entity, defined as “A chemical entity is a physical entity of interest in chemistry including molecular entities, parts thereof, and chemical substances.” *Chemical entity(*http://purl.obolibrary.org/obo/CHEBI_24431)  |
| **Mapping Elucidation:**       | The bonding between the atoms is not described and the concept is thus wider than the Ontocommons concept.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| **Semantic Relation Level:**   | *Strong Hierarchical*                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| **Mapping Axioms:**            | *ONTOCOMMONS:molecule rdfs:subClassOf CHEBI:molecule*                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |

RNXO

| **Target Ontology:**           | *http://purl.obolibrary.org/obo/rxno.owl*                                 |
|--------------------------------|---------------------------------------------------------------------------|
| **Related Ontology Entities:** | *MacroMolecule(http://purl.obolibrary.org/obo/CHEBI_33839)*               |
| **Mapping Elucidation:**       | *Molecule is not a class, and Macromolecule is aligned to CHEBI Ontology* |

MatOnto

| **Target Ontology:**           | *http://purl.obolibrary.org/obo/rxno.owl*                                                                                                                                        |
|--------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Related Ontology Entities:** | Molecule(<http://ontology.dumontierlab.com/Molecule>) Molecule is defined as “A collection of atoms of definite composition and connectivity held together by chemical bonds.”   |
| **Mapping Elucidation:**       | The bonds need not be e-bonds (electrostatic bonds are also chemical bonds) and the concept is thus wider.                                                                       |
| **Semantic Relation Level:**   | *Similarity (e.g. skos:related).*                                                                                                                                                |
| **Mapping Axioms:**            |                                                                                                                                                                                  |

EMMO

| **Target Ontology:**           | *http://emmo.info/emmo/1.0.0-beta4*                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
|--------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Related Ontology Entities:** | Molecule(http://emmo.info/emmo\#EMMO_3397f270_dfc1_4500_8f6f_4d0d85ac5f71) Molecule is defined as “An atom_based state defined by an exact number of e-bonded atomic species and an electron cloud made of the shared electrons.”   It is a subclass of Molecular Entity that is defined as “Any constitutionally or isotopically distinct atom, molecule, ion, ion pair, radical, radical ion, complex, conformer etc., identifiable as a separately distinguishable entity.” Molecular Entity [http://emmo.info/emmo\#EMMO_21205421_5783_4d3e_81e5_10c5d894a88a](about:blank#EMMO_21205421_5783_4d3e_81e5_10c5d894a88a)  Molecular Entity is a subclass of Matter, defined as “A 'Physical' that possesses some 'Lepton' or 'Quark' parts in each of its temporal parts.”  Matter(http://emmo.info/emmo\#EMMO_5b2222df_4da6_442f_8244_96e9e45887d1)  |
| **Mapping Elucidation:**       | *Equivalence*                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| **Semantic Relation Level:**   | *Equivalence (strong mapping)*                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| **Mapping Axioms:**            |  *owl:equivalentClass*                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |