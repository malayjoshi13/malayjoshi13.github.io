---
#layout: archive
permalink: /projects/
author_profile: true
---

<div class="research-block">
	<div class="left">
		<span class="research-img">
			<img src="/images/NMT_gif.gif">
		</span>
	</div>
	<div class="right">
		<div class="title">Dissecting-Transformers: Attempt to understand and use Transformers in-depth</div>
		<div class="sub-title">Started on Nov 2023 | <a target="_blank" class="tab_paper"  href="https://github.com/malayjoshi13/Understanding-Transformer">Project Page for Project1</a> | <a target="_blank" class="tab_paper"  href="https://github.com/malayjoshi13/NeuralMachineTranslator">Project Page for Project2</a></div>
		<div class="sub-title">Tech: Language Models, Pytorch, Python, Tensorboard, HuggingFace, Streamlit, Docker</div>		
		<span class="research-text">First work was around building vanilla Transformer from scratch and training it on iitb-english-hindi's sub-set of test datatset for the task of Machine Translation. Got BLEU score of 0.61, Character Error Rate of 0.16 and Word Error Rate of 0.35, Train loss of 1.50 and Val loss of 1.53. Second work was around building Machine Translation web-app using SoTA Encoder-Decoder-based Pre-trained Language Models for getting hands-on experience of working with LMs on a real-case at production level.</span>
	</div>
</div>


<div class="research-block">
	<div class="left">
		<span class="research-img">
			<img src="/images/drishti_gif.gif">
		</span>
	</div>
	<div class="right">
		<div class="title">Drishti: Visual Navigation Assistant for Visually Impaired</div>
		<div class="sub-title">Started on Sept 2022 | <a target="_blank" class="tab_paper"  href="https://iopscience.iop.org/article/10.1088/1742-6596/2570/1/012032">Paper</a> | <a target="_blank" class="tab_paper"  href="/files/Drishti_Report.pdf">Project Report</a> </div>
		<div class="sub-title">Tech: Computer Vision, Transfer Learning, Text-to-Speech, Google Cloud Platform (GCP), Python, TensorFlow, TensorBoard, Electronics Design and Integrations, Microcontroller Programming, Power Management, Mechanical Design </div>		
		<span class="research-text">Despite the development of numerous assistive devices over the years; due to various limitations, numerous visually impaired individuals in India still don’t have a navigational assistive tool/device. After reviewing related literature, informal discussions with visually impaired individuals, and a formal survey conducted at Raghuveer Singh Memorial Blind Trust in Shahdara (Delhi), my comprehension of this problem significantly improved. To address it, I developed an initial-stage low-cost eye-wear assistive device and conducted a test with a group of visually impaired participants. This work started as part of my Final-year College Project, and I am actively working to improve this solution.</span>
	</div>
</div>


<div class="research-block">
	<div class="left">
		<span class="research-img">
			<img src="/images/Pehchaan_gif.gif">
		</span>
	</div>
	<div class="right">
		<div class="title">Pehchaan</div>
		<div class="sub-title">Started in July 2022 | <a target="_blank" class="tab_paper"  href="https://github.com/malayjoshi13/Pehchaan">Project Page</a></div>
		<div class="sub-title">Tech: Deep Learning, Face detection, Face recognition, Tensorflow, Streamlit</div>		
		<span class="research-text"> Pehchaan is a one-shot labeling tool to identify the name of the person present in an image. It makes use of pre-trained Face detection model, Face alignment model, Face recognition model and algorithms to keep checking if the database is modified and doing one-to-one matching between feature representation of image input by user and image(s) in database. This tool is an attempt to automate the process of labeling the people present in photographs. In it's absence, it's a very time-consuming and labor-intensive task to manually label people present in a large stock of photographs and without these labels, these significant photographs are mere pieces of memory/space-consuming items. This work is representative of work done as part of my internship at DESIDOC-DRDO (New Delhi, India).</span>
	</div>
</div>


<div class="research-block">
	<div class="left">
		<span class="research-img">
			<img src="/images/gsoc_gif.gif">
		</span>
	</div>
	<div class="right">
		<div class="title">OligoFinder: Bio-NER System to Extract Oligonucleotide Entities</div>
		<div class="sub-title">Started on June 2022 | <a target="_blank" class="tab_paper"  href="https://summerofcode.withgoogle.com/programs/2022/projects/5b96vIqa">Project Page</a></div>
		<div class="sub-title">Tech: Pre-trained Language Model (BioBERT), Named Entity Recognition (NER), Python, TensorFlow, Google Cloud Platform (GCP), TensorBoard, FastAPI</div>		
		<span class="research-text">Methods to extract textual references of oligonucleotides have remained limited to being a time-consuming manual process with the inability to generalize to newer variations. To address these limitations, OligoFinder is developed as part of the Google Summer of Code'22 program at EMBL-EBI. It is a scalable and semi-automated Bio-NER system for identifying and extracting Oligonucleotide mentions and related data from Biomedical research papers.</span>
	</div>
</div>


<!-- <div class="research-block">
	<div class="left">
		<span class="research-img">
			<img src="/images/teasers/faceoff.gif">
		</span>
	</div>
	<div class="right">
		<div class="title">News-Shell</div>
		<div class="sub-title">Started in July 2022 | <a target="_blank" class="tab_paper"  href="add link">project page</a></div>
		<div class="sub-title">Tech: add tech </div>		
		<span class="research-text"> tell about project....extension of work "ShortRead" (add link of ShortRead project) started in Dec 2021.......</span>
	</div>
</div> -->


<div class="research-block">
	<div class="left">
		<span class="research-img">
			<img src="/images/talkinghand_gif.gif">
		</span>
	</div>
	<div class="right">
		<div class="title">TalkingHand: Sign Language Converter</div>
		<div class="sub-title">Started in May 2021 | <a target="_blank" class="tab_paper"  href="https://github.com/malayjoshi13/TalkingHand">Project Page</a></div>
		<div class="sub-title">Tech: Computer Vision, Transfer-Learning, Python, TensorFlow </div>		
		<span class="research-text"> TalkingHand is a Computer Vision and Deep Learning-based Sign Language to Text Conversion System which with the help of fine-tuned CNN of VGG16, classifies and converts the hand gestures made by the user into corresponding text-based labels.	Custom dataset of about 4000 images each for 6 labels has been collected for fine-tuning the CNN model using a combination of background subtraction (BackgroundSubtractorMOG2) and color threshold techniques so that data collected will have a lower bias due to the shape & colour of user's hand making the gesture and altering lightning conditions. Got following results after fine-tuning: train loss: 0.0188, train accuracy: 0.9965, validation loss: 0.0913 and validation accuracy: 0.9888. The objective of this system is to take first step towards developing a solution to help people with speaking and hearing disability to communicate with other people.

</span>
	</div>
</div>


<div class="research-block">
	<div class="left">
		<span class="research-img">
			<img src="/images/describer_gif.gif">
		</span>
	</div>
	<div class="right">
		<div class="title">Describer: Image Captioning System</div>
		<div class="sub-title">Started on Apr 2020 | <a target="_blank" class="tab_paper"  href="https://github.com/malayjoshi13/Describer">Project Page</a></div>
		<div class="sub-title">Tech: Computer Vision, NLP, Transfer-Learning, Flask, Python, TensorFlow </div>		
		<span class="research-text">Describer is an Image Captioning System which generates textual captions describing the images fed to it. This system consists of CNN model (built from scratch) and LSTM model. InceptionV3 model is used to generate image embeddings and GloVe 200-dim model is used to generate embeddings of captions. Whole system is trained on Flickr8k data. Achieved BLEU-1 score of 0.79 on test dataset. The objective of this system is to take first step towards developing a solution to help visually impaired people understands image-based information on their electronic devices and in their surroundings.
		</span>
	</div>
</div>


<div class="research-block">
	<div class="left">
		<span class="research-img">
			<img src="/images/Sanrakshan_gif.gif">
		</span>
	</div>
	<div class="right">
		<div class="title">Sanrakshan: Animal Deterrent Device</div>
		<div class="sub-title">Started on Jan 2020 | <a target="_blank" class="tab_paper" href="https://malayjoshi13.github.io/files/Sanrakshan_Report.pdf">Project Report</a> <a target="_blank" class="tab_paper" href="https://drive.google.com/file/d/1eC4c6zvbNNxLtWwpwbPqL4ohY22w0u4Z/view?usp=sharing">Video of Phase1</a> <a target="_blank" class="tab_paper" href="https://drive.google.com/file/d/1s_1gYTDBr2nosnFjSVyBHP34kpsHunBV/view?usp=sharing">Video of Phase2</a> </div>
		<div class="sub-title">Tech: Electronics Design and Integrations, Microcontroller Programming, Power Management, Mechanical Design</div>		
		<span class="research-text"> Farmers of Uttarakhand face the problem of crop destruction caused by wild animals. To address the limitations of existing solutions, we propose Sanrakshan, an animal deterrent device which prevents wild animals from destroying crops by use of "Laser-LDR Detection Technology". This solution works on the principle of using time-of-blocking of laser light reaching the LDR sensor to differentiate between humans and target animals. This work results from extensive involvement in the SIH'2020 competition with two other team members, Abhay Jaiswal and Maitreyi.</span>
	</div>
</div>