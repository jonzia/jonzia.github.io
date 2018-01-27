## Hail and Well Met, Traveler!

I'm an aspiring physician-scientist based in Atlanta, GA, USA. What does that mean, exactly? Well, it means that I love to code but I knew better than to make it my day job (that wouldn't be doing anybody any favors). On occasion, though, a project comes along that I'm really proud of and I'd like to share it with you! 

You can check out all my projects on my (admittedly sparsely-updated) **[GitHub Profile](https://github.com/jonzia)** -- or simply scroll down for project descriptions and links to their official sites. While my featured repositories are generally the only ones I can get around to updating, feel free to bookmark any of these pages to stay up-to-date with the most recent versions or **[contact me directly](https://www.jonzia.me)** if there's something you wish I'd pay more attention to.

My vast social media empire also includes [Facebook](https://www.facebook.com/jonathanzia), [YouTube](https://www.youtube.com/channel/UCYiktVuCaENeUPtyB5fBQuw/featured?disable_polymer=1), and [LinkedIn](https://www.linkedin.com/in/jonathanzia/).

I hope you find one or more of these repositories helpful and/or inspirational!


## Current and Featured Projects
Robust and validated programs that are updated more frequently... or just what I'm most excited about at the moment.

#### LSTM Network (Tensorflow)
This program is an LSTM network written in Python for Tensorflow. The architecture of the network is fully-customizable within the general framework, namely an LSTM network trained with a truncated BPTT algorithm where the output at each timestep is fed through a fully-connected layer to a variable number of outputs. The error is calculated via `tf.losses.mean_squared_error` and reduced via `tf.train.AdamOptimizer()`.

**[Official Site](https://jonzia.github.io/LSTM_Network/)**

#### Neural Net Studio (Matlab)
This program trains and analyzes recurrent neural networks (RNNs) as well as non-recurrent feedforward networks. It works for both recurrent and non-recurrent networks, and any number of different neural network architectures can be tested at once. The program is automatically formatted for parallel processing across computer cores. Check out the new GUI on [Youtube](https://www.youtube.com/watch?v=WBxCHDFzexQ)!

**[Official Site](https://jonzia.github.io/NeuralNetStudio/)**

#### Drone Flight Controller (Arduino)
Check back soon!


## Other Projects
More sparsely-updated projects mainly for experimentation... or just less interesting (*cough* Wordnet *cough*).

#### Wordnet Data Capture (Java)
The purpose of this program is to scan the Princeton Wordnet database and store the hyponym and meronym data as well as full hypernym trees such that this data may be analyzed by another program. This program uses the JWI API from MIT to read and translate the Wordnet 3.0 database into workable .txt files for use in applications such as MATLAB. This program was used to build the dataset for the [Codenames AI](https://github.com/jonzia/Codenames) also available on GitHub.

**[Official Site](https://jonzia.github.io/WordnetDataCapture/)**

#### Object Tracking using OpenCV (C++)
This program uses the OpenCV computer vision library to filter objects based on color.

**[Official Site](https://jonzia.github.io/ObjectTracking/)**

#### Object Classification (Matlab)
This program is a basic implementation of object classification using MATLAB. The current iteration classifies handwritten numbers based on the MNIST dataset (training files included in repository), however it may be modified for different architectures and purposes. After training the neural network (either deep neural network or convolutional neural network) to recognize the digits, the program recognizes digits visible through the computer webcam.

**[Official Site](https://jonzia.github.io/ObjectClassification/)**

## Games!
Sometimes I design programs for games that I have a hard time winning.

#### Codenames AI (Matlab)
This program generates clues based on either 8 or 9 words entered by the user. The words must be taken from the 400-word set of the Codenames board game. The clues are generated based on an analysis of the Priceton Wordnet database. You can check out a demo of the program on [YouTube](https://youtu.be/yX2YkhvAtM4)!

**[Official Site](https://jonzia.github.io/Codenames/)**

### Sudoku Solver (Matlab)
Written on an airplane when I couldn't find the answer page in the magazine. Also on [YouTube](https://youtu.be/QC-4RXylWQ0) because why not?

**[Official Site](https://jonzia.github.io/Sudoku/)**
