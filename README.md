# papers
Lista de papers para ler em um domingo chuvoso

### Deep learning
[Learning Individual Styles of Conversational Gesture](https://arxiv.org/pdf/1906.04160.pdf)
> Human speech is often accompanied by hand and arm gestures. Given audio speech input, we generate plausible gestures to go along with the sound. Specifically, we perform cross-modal translation from “in-the-wild” monologue speech of a single speaker to their hand and arm motion. We train on unlabeled videos for which we only have noisy pseudo ground truth from an automatic pose detection system. Our proposed model significantly outperforms baseline methods in a quantitative comparison. To support research toward obtaining a computational understanding of the relationship between gesture and speech, we release a large video dataset of person-specific gestures.

[Online Deep Learning: Learning Deep Neural Networks on the Fly](https://arxiv.org/pdf/1711.03705.pdf)
> Deep Neural Networks (DNNs) are typically trained by back-propagation  in  a  batch  learning  setting,  which  requires  theentire training data to be made available prior to the learn-ing task. This is not scalable for many real-world scenarioswhere  new  data  arrives  sequentially  in  a  stream  form.  Weaim  to  address  an  open  challenge  of  “Online  Deep  Learn-ing” (ODL) for learning DNNs on the fly in an online setting.Unlike traditional online learning that often optimizes someconvex  objective  function  with  respect  to  a  shallow  model(e.g., a linear/kernel-based hypothesis), ODL is significantlymore  challenging  since  the  optimization  of  the  DNN  ob-jective function is non-convex, and regular backpropagationdoes not work well in practice, especially for online learningsettings. In this paper, we present a new online deep learningframework that attempts to tackle the challenges by learningDNN models of adaptive depth from a sequence of trainingdata in an online learning setting. In particular, we propose anovel Hedge Backpropagation (HBP) method for online up-dating the parameters of DNN effectively, and validate the ef-ficacy of our method on large-scale data sets, including bothstationary and concept drifting scenarios.

[A Universal Music Translation Network]()
> We present a method for translating music across musical instruments, genres, and styles. This method is based on a multi-domain wavenet autoencoder, with a shared encoder and a disentangled latent space that is trained end-to-end on waveforms. Employing a diverse training dataset and large net capacity, the domain-independent encoder allows us to translate even from musical domains that were not seen during training. The method is unsupervised and does not rely on supervision in the form of matched samples between domains or musical transcriptions. We evaluate our method on NSynth, as well as on a dataset collected from professional musicians, and achieve convincing translations, even when translating from whistling, potentially enabling the creation of instrumental music by untrained humans.
