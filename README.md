# Book Sequencer

Sequence a book from a source based on a term dictionary.

# Basic Types

Ord, Int

# In

Source
?dictionary:Dict
?order:Dict -> Dict -> Ord
?strategy:Strat
?timeout:Dict -> Int

# Built ins

sequence:Source -> Sequence
book:Sequence -> Book
optimized:Strat -> Dict -> ?order -> ?timeout -> Sequence
