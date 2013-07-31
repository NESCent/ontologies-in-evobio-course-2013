This example extends the previous disjoint classes example to include class expressions

(advanced)

Constructs illustrates:

 * Disjoint class expressions

Instructions:

# Open bad-chromosome-2.owl
  * Note: The following two questions use the pattern of the previous examples, except we have removed the "nuclear part" and "mitochondrial part" terms.
# Do a query for all parts of a nucleus - how many classes are returned?
# Do a query for all parts of a mitochondrion - how many classes are returned?
  * Based on the two queries above can you tell what the (biological) problem with chromosome is?
# Now the tricky bit.  Add a disjoint axiom (somewhere) that will illustrate the problem with chromosome when the reasoner is used.
  # Remember to use HermiT and refresh your reasoning when you add an axiom.
  # Hint: Our goal in adding a disjoint axiom is to classify "chromosome" as Nothing.

To conclude:

# Add a class called 'test class', and make it a subclass of "nucleus" and a subclass of "mitochondrion"
# Is it satisfiable? If so, why? How would you make this class unsatisfiable?

