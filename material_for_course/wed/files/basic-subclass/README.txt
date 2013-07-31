This example illustrates adding classes and class annotations into an existing SubClass hierarchy.
* The example does not make use of reasoning / automated classification or class expressions.

Constructs illustrated:

 * SubClasses (adding them)
 * Annotations
 * DatabaseCrossReferences (=xref)

Instructions:

# Open chromosome-parts.owl

== Subclasses ==

# Add the class "replication fork" to the ontology under "chromosomal part".
  * Don't worry about the ID

Moving around classes: 
# Add the term "intracellular non-membrane-bounded organelle" as a SubClass of "Thing"
# Move it, by dragging and dropping, to place it as a Subclass of 'non-membrane-bounded organelle' 

== Annotations == 

* The goal is to _replicate the existing information from GO_ on the "replication fork" class. 

# Click on the 'replication fork' class you just created.  
  # Use the (+) next to Annotations to add an annotation.
  * You can find the annotation values to add in GO, or in the HINTS.obo file
  # Add the following (using the values that you found)
    # A text definition for the class
      # Click on the "replication fork" class, then click (+) by Annotations
      # Choose the "Constant" tab
      # Click (select) "definition" on the left
      # Enter the definition in the "Value" window.  You can leave Type and Lang blank.
      # Click OK. THe annotation should appear in the Annotations window.
    # 2 dbxrefs to the text definition
      # Click the (@) icon beside the definition annotation
      # Click the (+) beside annotations
      # Select "database_cross_reference" in the left pane
      # Enter a value. 
      # Repeat for the other cross reference by clicking (+) in the "Annotations for AnnotationsAssertion window" that follows
    # A related synonym
      # Add an annotation to "replication fork" with the (+)
      # Choose "has_related_synonym" and enter the value
    # An xref to the class itself

Synonym properties:

# Add the SubClass "site of double-strand break" to the ontology under "chromosomal part"
 # Add a synonym dbxref annotation. E.g. synonym: "site of DSB" has_exact_synonym [PMID:21035408]
    # In the Annotations window click (+) to add an annotation
    # Select "has_exact_synonym"
    # In the Constant tab, in the value field, add "site of DSB"
    # In the value field add has_exact_synonym with annotation[PMID:21035408]", click to continue.  Notice that the synonym annotation (@) is now yellow indicating it has an annotation.
    * What is the difference between an exact and narrow synonym?

# (Bonus) Replicate the remaining annotations found in the OBO file for this class  

