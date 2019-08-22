# Poem-Generator
Poem generator using RNN architecture for generation poem's like Shakespeare

A similar (but more complicated) model as (Name-Generator) is to generate Shakespeare poems. Instead of learning from a dataset of names you can use a collection of Shakespearian poems. Using LSTM cells, you can learn longer term dependencies that span many characters in the text--e.g., where a character appearing somewhere a sequence can influence what should be a different character much much later in ths sequence. These long term dependencies were less important with names, since the names were quite short.
