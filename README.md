# blog
pprint() でリストや辞書を整形して出力するテクニックを試しました  

dic = {  
            'C134':{"price":30,"sales":"1000","profit":200 ,"alist":[110,20,30 ,50]},   
            'C623':{"price":80,"sales":"100" ,"profit":6   ,"alist":[100,10,30 ,50]},  
            'C430':{"price":70,"sales":"5000","profit":1000,"alist":[160,11,120,6]},  
            'C115':{"price":10,"sales":"2400","profit":40  ,"alist":[80 , 1,10 ,6]}  
        }  
        
jupyerでprint(dic)などでそのまま表示すると、詰めて表示されますが、  

import pprint  
pprint.pprint(dic)  

とすると、表示がキレイにインデントされます。  
