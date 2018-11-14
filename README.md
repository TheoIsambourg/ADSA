# ADSA PROJECT : Lili Reader
  
 

What is  Lili Reader  ? 
Lili Reader is an algorithm able to identify the context of a word in a sentence by reading the full sentence and returning the aim of this word in the sentence. It should compare every words to template sentences and recognise structures.  
 
 



//////////Objective of  Lili Reader//////////

Thanks to the information deduced, Lili Reader adapt the font of the text, taking into account the needs of a dislexyque reader. 
 
 
Inputs :
1 - The user defines the parameters of his needs for reading easily (type of fonts) 
2 - The user enter a sentence  
 
Outputs :
The sentence is edited and adpated to the needs of the reader.  
 
/////////////////////////////////////////////





//////////Overall strategies to solve the challenge//////////
 
 
First problematic :
We will apply the divide and conquer method to get the function of each word in the sentence. Indeed, in order to recognize the function of each word in the sentence we must understand the connections that can be between each word. But for that you must first know the meaning of each word. For the algorithm, to understand a word is to associate it with its correct definition. The first problem that arises here is that a word can have different forms for the same meaning and different meanings for the same form.
 
 
Second problematic :
Once the meaning of each of the words found, the second problem is to determine the function of this word. The function of each of them depends on their place in the sentence. Guided by the grammatical rules coupled to the meanings of the words can then for each word know what relation it has with each other of the words of the sentence. These relationships then form a tree.
 
 ///////////////////////////////////////////////////////////////


 

Nhu Vuong Mavier &  Théo Isambourg .


 
