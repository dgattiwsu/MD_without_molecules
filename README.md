# MD_without_molecules

Molecular dynamics without molecules: searching the conformational space of proteins with generative neural networks

Gregory Schwing 1,5,‡, Luigi L. Palese 2,‡, Ariel Fernández 3,4, Loren Schwiebert 1, Domenico L. Gatti 5

1 Department of Computer Science, College of Engineering, Wayne State University, Detroit, USA

2 Department of Basic Medical Sciences, Neurosciences and Sense Organs, Univ. of Bari Aldo Moro, Bari, Italy

3 National Research Council (CONICET), Buenos Aires 1033, INIQUISUR-CONICET, Av. Alem 1253, Bahía Blanca 8000, Argentina

4 Daruma Institute for Applied Intelligence, AF Innovation, Pharma Consultancy, 1005 Oakhurst Avenue, NC 27262, USA

5 Department of Biochemistry, Microbiology, and Immunology, Wayne State University School of Medicine, Detroit, USA

‡These authors contributed equally to the study.

gregory.schwing@med.wayne.edu

luigileonardo.palese@uniba.it

ariel@afinnovation.com

loren@wayne.edu

dgatti@med.wayne.edu


Abstract

All-atom and coarse-grained molecular dynamics are two widely used computational tools to study the conformational states of proteins. Yet, these two simulation methods suffer from the fact that without access to supercomputing resources, the time and length scales at which these states become detectable are difficult to achieve. One alternative to such methods is based on encoding the atomistic trajectory of molecular dynamics as a “shorthand” version devoid of physical particles, and then learning to propagate the encoded trajectory through the use of artificial intelligence. Here we show that a simple ‘textual’ representation of the frames of molecular dynamics trajectories as vectors of Ramachandran basin classes retains most of the structural information of the full atomistic representation of a protein in each frame, and can be used to generate equivalent atom-less trajectories suitable to train different types of generative neural networks. In turn, the trained generative models can be used to extend indefinitely the atom-less dynamics or to sample the conformational space of proteins from their representation in the models latent space. We define intuitively this methodology as molecular dynamics without molecules, and show that it enables to cover physically relevant states of proteins that are difficult to access with traditional molecular dynamics. 
