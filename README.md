# Hybrid-model-to-predict-ICC-activity-from-efferent-cholinergic-neuron-stimulation
This code belongs to a hybrid model which is mechanistic model (michaelis menten equation using hill coefficient) and a Multilayer Perceptron to predict Interstitial Cells of Cajal (ICC) activity (frequency and amplitude) from efferent cholinergic neuron pathway stimulation. The hybrid model is an example of a Physics Informed Neural Network as it has mechanistic and AI components.

A simulated synthetic dataset of ICC frequency (cpm) and amplitude in the antrum, using mechanistic curves for acetylcholine (ACh) release and its excitatory modulation on ICC activity. Animal-to-animal variability is introduced, and Gaussian noise is added to mimic experimental measurements. The simulation spans multiple animals and is informed by values reported in experimental studies, producing both individual and mean ICC responses across efferent input levels.

The generation of synthetic data is inflenced by literature studies [1-3]
 [1] D. M. Kim, T. M. Khing, W. Thein, W. S. Choi, C. Y. Shin, U. D. Sohn, Signaling pathways underlying changes in the contractility of the stomach fundus smooth muscle in diabetic rats, Archives of pharmacal research 43 (2020) 666–675.

[2] L. M. da Silva, L. d. M. Burci, S. Crestani, P. de Souza, R. d. C. M. V. d. A. F. da Silva, N. Dartora, L. M. de Souza, T. R. Cipriani, J. E. da Silva-Santos,
E. Andre, et al., Acid-gastric antisecretory effect of the ethanolic extract from ´ arctium lappa l. root: role of h+, k+-atpase, ca 2+ influx and the cholinergic pathway, Inflammopharmacology 26 (2018) 521–530.

[3] Zhang RX, Wang XY, Chen D, Huizinga JD. Role of interstitial cells of Cajal in the generation and modulation of motor activity induced by cholinergic neurotransmission in the stomach. Neurogastroenterol Motil. 2011 Sep;23(9):e356-71. doi: 10.1111/j.1365-2982.2011.01753.x. Epub 2011 Jul 22. PMID: 21781228.
