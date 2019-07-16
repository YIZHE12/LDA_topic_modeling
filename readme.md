Assumptions:

- Documents with similar topics will use similar groups of words

- Documents definitions/modeling:

-- Documents are probability distributions over latent topics

-- Documents are probability distributions over words



Alpha: per-document topic distribution

A large alpha means each document is responsible for a mixture of topics and not a single one. A small alpha menas the document can be represented by only a few topics.

High alpha will make documents more similar to each other

Belta: per-topic words distribution

A large belta means a topic has a large mixture of words while a small belta means a topic only contains a few words.

High belta will make topics more similar to each other.


LDA space is a simplex with the number of dimensions = number of topics we asked it to make.


