# Detecting malaria with deep learning
## <i> P. Falciparum detection in thin blood smear images </i>
</br>
## Motivation </br>
Malaria is a deadly, infectious, mosquito-borne disease caused by Plasmodium parasites that are transmitted by the bites of infected female Anopheles mosquitoes. There are five parasites that cause malaria, but two types—P. falciparum and P. vivax—cause the majority of the cases.
</br>
The World Health Organization's (WHO) malaria facts indicate that nearly half the world's population is at risk from malaria, and there are over 200 million malaria cases and approximately 400,000 deaths due to malaria every year. This is a motivatation to make malaria detection and diagnosis fast, easy, and effective.
</br>
The standard malaria diagnosis is typically based on a blood-smear workflow, according to Carlos Ariza's article "Malaria Hero: A web app for faster malaria diagnosis," which I learned about in Adrian Rosebrock's "Deep learning and medical image analysis with Keras." I appreciate the authors of these excellent resources for giving me more perspective on malaria prevalence, diagnosis, and treatment.
</br>
Convolution layers learn spatial hierarchical patterns from data, which are also translation-invariant, so they are able to learn different aspects of images. For example, the first convolution layer will learn small and local patterns, such as edges and corners, a second convolution layer will learn larger patterns based on the features from the first layers, and so on. This allows CNNs to automate feature engineering and learn effective features that generalize well on new data points. Pooling layers helps with downsampling and dimension reduction.
</br>
Automated malaria detection using deep learning models like CNNs could be very effective, cheap, and scalable, especially with the advent of transfer learning and pre-trained models that work quite well, even with constraints like less data.
</br>
## Dataset
The data for our analysis comes from researchers at the Lister Hill National Center for Biomedical Communications (LHNCBC), part of the National Library of Medicine (NLM), who have carefully collected and annotated the publicly available dataset of healthy and infected blood smear images. These researchers have developed a mobile application for malaria detection that runs on a standard Android smartphone attached to a conventional light microscope. They used Giemsa-stained thin blood smear slides from 150 P. falciparum-infected and 50 healthy patients, collected and photographed at Chittagong Medical College Hospital, Bangladesh. The smartphone's built-in camera acquired images of slides for each microscopic field of view. The images were manually annotated by an expert slide reader at the Mahidol-Oxford Tropical Medicine Research Unit in Bangkok, Thailand.




