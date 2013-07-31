This illustrates basic DL (description logic) queries.

A DL query is a class expression that is constructed using constructs
such as "and" (corresponding to set intersection) and "some" (see
previous example).

Note that the example that follows this one also revisits DL queries.

Constructs used: "and", "some"

# Open cc.owl
# Turn on the Hermit Reasoner.
# Go to DL query tab
# Find all subtypes of 'chromosome'
# Experiment with the tab - what do the different checkboxes give you?
# Find all parts of a 'cytoplasm'
## There are two ways to express this using the current GO - can you find both ways? Do you get the same results?
# Find all 'chromosomes' that are part of a 'cytoplasm'
## Do this *without* using GO_0000229 (what is GO_0000229?). Using this class do you get the same results?

NEXT:

# Find all classes whose instances have a snRNP ('small nuclear ribonucleoprotein complex') as part
# Find all classes whose instances have both a U11 snRNP AND a U12 snRNP as parts
# Find all classes whose instances have both a U11 snRNP OR U12 snRNP as parts
# Create a class from the latter DL query using the "Add to the ontology" button.  Examine where this class is placed in the hierarchy.
