---
type: synthesis
tags:
  - planning
  - metalearning
status: seedling
---
# Folder Structure

/Concepts - the atomic notes that contain the information for topic
/Fleeting - quick captures, to be processed
/Maps - navigation and indexing notes used to organize
/Projects - study plans, problem sets, essays
/Sources - reference material, book notes, video notes, etc.

# Note Anatomy

Every note should begin with YAML frontmatter containing metadata. This metadata along with note linking will be the main structure of the compendium. Every note should include a type, at least one tag, and a status property.

### Property types

##### type
This property indicates the note type and can have one of the following values:
- concept: a note that describes one small concept (group, set, Hamiltonian, etc.)
- person: a note that describes a historical person (Isaac Newton, Albert Einstein, etc.)
- synthesis: a note that is an original work (essay, learning plan, timeline, etc.)
- map: a navigational note known as a map of content (MOC)
- source: notes on specific sources such as books, videos, and lectures

##### tags
This property is more general, but should usually include the domain, subdomain, and related topics.

##### status
This property denotes the current status of the note. It can take one of the following values:
