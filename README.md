# Discrimination-Game
Discriminative Language Game played by two quantised autoencoders

Two neural networks are set up to play a "Discrimination Game" similar to two people communicating using lingusitic concepts to find agreement in their representations and judgments. One network is based on the encoder and quantizer of a VQVAE. The other is loosely modelled on a decoder. The aim is for the discriminator to learn whether the compressed, quantized representation of an image is the same data as a copy of the original data, or a fake. 

The hypothesis is that this primitive model of lingusitic-cultural negotiation may lead to characteristic hierarchies in the learned quantized representations.

Similarly to how the hierarchy of colour concepts observed universally across human demographics has an information-theoretic explanation based in language-game playing, interacting agents (cf. paper "The Emergence of a Hierarchy of Colour Concepts")
