# Detection-Profanity-Words

this model is very useful to anyone who wants to develop a social app or anything that has a Comment Section To be able to detect profanity-Words that the User writes. 

DATA SOURCE: 
I Collected Different Data From Different Sources, and then created Data-Training included 


Arabic profane words    ,

English profane words   ,

franko profane words    ,

religions                ,

gender types in Arabic, English           ,

Women's bodies & clothes                    ,

man body & clothes                              ,

names of porn actors women & men in English    ,

names of porn actors women & men in Arabic      ,

Illegal emoji                        ,

Illegal Flags                ,

illegal Saudi words        ,


----------------------------------------------------------



Sample of Preprocessing used in the Model :
Processing :
if # then offensive
if links then offensive

Arabic :
Arabic_normalize_chars ()           , Implement the func to normalize characters
Arabic_remove_tashkeel()            , Implement the func to remove tashkeel 
Arabic_remove_H()    	            , Implement func to remove هاء from End word
en_ar_remove_punctuation()	    , Implement the func to remove punctuation
en_ar_remove_repeating_characters() , Implement the func to remove repeater charc


English :
en_singularize_word()		    , Implement the func to make the word singular
en_ar_remove_punctuation()	    , Implement the func to remove punctuation
en_ar_remove_repeating_characters() , Implement the func to remove repeater charc
