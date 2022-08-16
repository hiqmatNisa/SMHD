# SMHD
# Students Messy Handwritten Dataset

This repository contains handwritten samples from the SMH dataset and a permission form to access the data. The form's primary purpose is to know who is using this dataset and for what purpose they are using it. Send the form to hiqmat.nisa@gmail.com to get access. 


#Dataset Repository
In the central repository, you can see two subfolders .i.e, images and transcription files. Each subfolder in the images folder represents a different category. For instance, summary-based-0001-0055 contains 55 handwritten image documents related to the summary task. Therefore, the images start from 0001 and end with 0055 in this category. Similarly, in the following category, Mathematics-0056-0088, the images begin from 0056 and end with 0088. 
The second folder contains all the transcriptions files in the form of .txt files corresponding to the images. The transcription is available only at the document level. 

# Dataset Description

The widley used publicly dataset the IAM is free from different editing operations like cross-outs and corrections beacuse it has been produced in a controlled situation. In practice, however, we cannot make assumptions about the handwritten input documents. Therefore, the automatic conversion of unrestricted handwritten text into computer-readable text is still challenging. For instance, when a student takes handwritten notes during a class, places them in the scanner, and instructs the handwritten text recognizer to read them, it will likely produce arbitrary output. 

We have incorporated contributions from more than 500 students to construct the dataset. Handwritten examination papers are primary sources in academic institutes to assess student learning. In our experience as academics, we have found that student examination papers tend to be messy with all kinds of insertions and corrections and would thus be a great source of documents for investigating HTR in the wild. Unfortunately, student examination papers are not available due to ethical considerations. So, we created an exam-like situation to collect handwritten samples from students. The corpus of the collected data is academic-based. Usually, in academia, handwritten papers have lines in them. For this purpose, we drew lines using light colors on white paper. The height of a line is 1.5 pt and the space between two lines is 40 pt. The filled handwritten documents were scanned at a resolution of  300 dpi at a grey-level resolution of 8 bits. 

\subsection{Collection Process}
The collection process was done in four different ways. In the first exercise, we asked participants to summarize a given text in their own words. We called it a summary-based dataset. In the summary writing task, we included 60 undergraduate students studying the English language as a subject. After getting their consent, we distributed  printed text articles and we asked them to choose one article, read it and summarize it in  a paragraph in 15 minutes. The corpus of the printed text articles given to the participants was collected from the Internet on different topics. The articles were related to current political situations, daily life activities, and the Covid-19 pandemic. 

In the second exercise, we asked participants to write an essay from a given list of topics, or they could write on any topic of their choice. We called it an essay-based dataset. This dataset is collected from 250 High school students. We gave them 30 minutes to think about the topic and write for this task.

 In the third exercise,  we select participants from different subjects and ask them to write on a topic from their current study. We called it a subject-based dataset. For this study, we used undergraduate students from different subjects, including 33 students from Mathematics, 71 from Biological Sciences, 24 from Environmental Sciences,  17 from Physics, and more than 84 from English studies. 

Finally a class-notes dataset, we have collected class notes from almost 35 students on the same topic. We asked students to take notes of every possible sentence the speaker delivered during the lecture. After finishing the lesson in almost 10 minutes, we asked students to recheck their notes and compare them with other classmates. We did not impose any time restrictions for rechecking. We observed more cross-outs and corrections in class-notes compared to summary-based and academic-based collections.  

In all four exercises, we did not impose any rules on them, for example, spacing, usage of a pen, etc. We asked them to cross out the text if it seemed inappropriate. Although usually writers made corrections in a second read, we also gave an extra 5 minutes for correction purposes. 
