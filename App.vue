{\rtf1\ansi\ansicpg949\cocoartf2580
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fnil\fcharset0 Menlo-Regular;\f1\fnil\fcharset129 AppleSDGothicNeo-Regular;}
{\colortbl;\red255\green255\blue255;\red109\green109\blue109;\red23\green23\blue23;\red70\green137\blue204;
\red202\green202\blue202;\red140\green211\blue254;\red194\green126\blue101;\red167\green197\blue152;\red183\green111\blue179;
\red212\green214\blue154;\red66\green179\blue255;\red89\green138\blue67;}
{\*\expandedcolortbl;;\cssrgb\c50196\c50196\c50196;\cssrgb\c11765\c11765\c11765;\cssrgb\c33725\c61176\c83922;
\cssrgb\c83137\c83137\c83137;\cssrgb\c61176\c86275\c99608;\cssrgb\c80784\c56863\c47059;\cssrgb\c70980\c80784\c65882;\cssrgb\c77255\c52549\c75294;
\cssrgb\c86275\c86275\c66667;\cssrgb\c30980\c75686\c100000;\cssrgb\c41569\c60000\c33333;}
\paperw11900\paperh16840\margl1440\margr1440\vieww11520\viewh8400\viewkind0
\deftab720
\pard\pardeftab720\sl360\partightenfactor0

\f0\fs24 \cf2 \cb3 \expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 <\cf4 \strokec4 template\cf2 \strokec2 >\cf5 \cb1 \strokec5 \
\pard\pardeftab720\sl360\partightenfactor0
\cf5 \cb3   \cf2 \strokec2 <\cf4 \strokec4 div\cf5 \strokec5  \cf6 \strokec6 class\cf5 \strokec5 =\cf7 \strokec7 "container"\cf2 \strokec2 >\cf5 \cb1 \strokec5 \
\cb3  \cf2 \strokec2 <\cf4 \strokec4 div\cf5 \strokec5  \cf6 \strokec6 class\cf5 \strokec5 =\cf7 \strokec7 "list-group"\cf2 \strokec2 >\cf5 \cb1 \strokec5 \
\cb3   \cf2 \strokec2 <\cf4 \strokec4 a\cf5 \strokec5  \cf6 \strokec6 v-for\cf5 \strokec5 ="\cf6 \strokec6 board\cf5 \strokec5  \cf4 \strokec4 in\cf5 \strokec5  \cf6 \strokec6 data\cf5 \strokec5 .\cf6 \strokec6 boardList\cf5 \strokec5 " \cf6 \strokec6 v-bind\cf5 \strokec5 :\cf6 \strokec6 key\cf5 \strokec5 ="\cf6 \strokec6 board\cf5 \strokec5 .\cf6 \strokec6 boardSequence\cf5 \strokec5 " \cf6 \strokec6 class\cf5 \strokec5 =\cf7 \strokec7 "list-group-item list-group-item-action active"\cf5 \strokec5  \cf6 \strokec6 aria-current\cf5 \strokec5 =\cf7 \strokec7 "true"\cf2 \strokec2 >\cf5 \cb1 \strokec5 \
\cb3     \cf2 \strokec2 <\cf4 \strokec4 div\cf5 \strokec5  \cf6 \strokec6 class\cf5 \strokec5 =\cf7 \strokec7 "d-flex w-100 justify-content-between"\cf2 \strokec2 >\cf5 \cb1 \strokec5 \
\cb3       \cf2 \strokec2 <\cf4 \strokec4 h5\cf5 \strokec5  \cf6 \strokec6 class\cf5 \strokec5 =\cf7 \strokec7 "mb-1"\cf2 \strokec2 >
\f1 \cf5 \strokec5 \'c1\'a6\'b8\'f1
\f0  : \{\{\cf6 \strokec6 board\cf5 \strokec5 .\cf6 \strokec6 boardtopic\cf5 \strokec5 \}\}\}\cf2 \strokec2 </\cf4 \strokec4 h5\cf2 \strokec2 >\cf5 \cb1 \strokec5 \
\cb3       \cf2 \strokec2 <\cf4 \strokec4 small\cf2 \strokec2 >
\f1 \cf5 \strokec5 \'c1\'b6\'c8\'b8\'bc\'f6
\f0  : \{\{\cf6 \strokec6 board\cf5 \strokec5 .\cf6 \strokec6 nClick\cf5 \strokec5 \}\}\cf2 \strokec2 </\cf4 \strokec4 small\cf2 \strokec2 >\cf5 \cb1 \strokec5 \
\cb3       \cf2 \strokec2 <\cf4 \strokec4 small\cf2 \strokec2 >
\f1 \cf5 \strokec5 \'b3\'af\'c2\'a5
\f0  : \{\{\cf6 \strokec6 board\cf5 \strokec5 .\cf6 \strokec6 rdate\cf5 \strokec5 \}\}\cf2 \strokec2 </\cf4 \strokec4 small\cf2 \strokec2 >\cf5 \cb1 \strokec5 \
\cb3     \cf2 \strokec2 </\cf4 \strokec4 div\cf2 \strokec2 >\cf5 \cb1 \strokec5 \
\cb3     \cf2 \strokec2 <\cf4 \strokec4 small\cf2 \strokec2 >
\f1 \cf5 \strokec5 \'b1\'db\'be\'b4\'c0\'cc
\f0  : \{\{\cf6 \strokec6 board\cf5 \strokec5 .\cf6 \strokec6 userid\cf5 \strokec5 \}\}\cf2 \strokec2 </\cf4 \strokec4 small\cf2 \strokec2 >\cf5 \cb1 \strokec5 \
\cb3   \cf2 \strokec2 </\cf4 \strokec4 a\cf2 \strokec2 >\cf5 \cb1 \strokec5 \
\
\cb3   \cf2 \strokec2 <\cf4 \strokec4 a\cf5 \strokec5  \cf6 \strokec6 v-if\cf5 \strokec5 ="\cf6 \strokec6 data\cf5 \strokec5 .\cf6 \strokec6 boardList\cf5 \strokec5 .\cf6 \strokec6 length\cf5 \strokec5  == \cf8 \strokec8 0\cf5 \strokec5 " \cf6 \strokec6 class\cf5 \strokec5 =\cf7 \strokec7 "list-group-item list-group-item-action"\cf2 \strokec2 >\cf5 \cb1 \strokec5 \
\cb3       
\f1 \'b0\'d4\'bd\'c3\'b9\'b0\'c0\'cc
\f0  
\f1 \'c1\'b8\'c0\'e7\'c7\'cf\'c1\'f6\'be\'ca\'bd\'c0\'b4\'cf\'b4\'d9
\f0 .\cb1 \
\cb3   \cf2 \strokec2 </\cf4 \strokec4 a\cf2 \strokec2 >\cf5 \cb1 \strokec5 \
\
\pard\pardeftab720\sl360\partightenfactor0
\cf2 \cb3 \strokec2 </\cf4 \strokec4 div\cf2 \strokec2 >\cf5 \cb1 \strokec5 \
\cf2 \cb3 \strokec2 </\cf4 \strokec4 div\cf2 \strokec2 >\cf5 \cb1 \strokec5 \
\cf2 \cb3 \strokec2 </\cf4 \strokec4 template\cf2 \strokec2 >\cf5 \cb1 \strokec5 \
\
\cf2 \cb3 \strokec2 <\cf4 \strokec4 script\cf2 \strokec2 >\cf5 \cb1 \strokec5 \
\pard\pardeftab720\sl360\partightenfactor0
\cf9 \cb3 \strokec9 import\cf5 \strokec5  \{ \cf6 \strokec6 reactive\cf5 \strokec5  \} \cf9 \strokec9 from\cf5 \strokec5  \cf7 \strokec7 '@vue/reactivity'\cf5 \cb1 \strokec5 \
\cf9 \cb3 \strokec9 import\cf5 \strokec5  \cf6 \strokec6 axios\cf5 \strokec5  \cf9 \strokec9 from\cf5 \strokec5  \cf7 \strokec7 'axios'\cf5 \cb1 \strokec5 \
\cf9 \cb3 \strokec9 export\cf5 \strokec5  \cf9 \strokec9 default\cf5 \strokec5  \{\cb1 \
\pard\pardeftab720\sl360\partightenfactor0
\cf5 \cb3   \cf6 \strokec6 name:\cf5 \strokec5  \cf7 \strokec7 'App'\cf5 \strokec5 ,\cb1 \
\cb3   \cf6 \strokec6 components:\cf5 \strokec5  \{\cb1 \
\cb3   \},\cb1 \
\cb3   \cf10 \strokec10 setup\cf5 \strokec5  () \{\cb1 \
\cb3     \cf4 \strokec4 const\cf5 \strokec5  \cf11 \strokec11 data\cf5 \strokec5  = \cf10 \strokec10 reactive\cf5 \strokec5 (\{\cb1 \
\cb3       \cf6 \strokec6 boardList:\cf5 \strokec5  []\cb1 \
\cb3     \})\cb1 \
\cb3     \cf12 \strokec12 // spring rest api 
\f1 \'b8\'a6
\f0  call 
\f1 \'c7\'cf\'bf\'a9
\f0  data list 
\f1 \'b8\'a6
\f0  select\cf5 \cb1 \strokec5 \
\cb3     \cf4 \strokec4 const\cf5 \strokec5  \cf10 \strokec10 getList\cf5 \strokec5  = () \cf4 \strokec4 =>\cf5 \strokec5  \{\cb1 \
\cb3       \cf12 \strokec12 // fetch('
\f1 \'b5\'a5\'c0\'cc\'c5\'cd\'b8\'a6
\f0  
\f1 \'b0\'a1\'c1\'ae\'bf\'c0\'b1\'e2
\f0  
\f1 \'c0\'a7\'c7\'d8
\f0  
\f1 \'c8\'a3\'c3\'e2\'c7\'d2
\f0  back-end 
\f1 \'c2\'ca\'c0\'c7
\f0  rest api')\cf5 \cb1 \strokec5 \
\cb3       \cf11 \strokec11 axios\cf5 \strokec5 .\cf10 \strokec10 get\cf5 \strokec5 (\cf7 \strokec7 'http://localhost:8082/project/JsonBoard_view?pageNum=1'\cf5 \strokec5 )\cb1 \
\cb3         .\cf10 \strokec10 then\cf5 \strokec5 (\cf6 \strokec6 res\cf5 \strokec5  \cf4 \strokec4 =>\cf5 \strokec5  \{\cb1 \
\cb3           \cf6 \strokec6 console\cf5 \strokec5 .\cf10 \strokec10 log\cf5 \strokec5 (\cf6 \strokec6 res\cf5 \strokec5 )\cf12 \strokec12 // data\cf5 \cb1 \strokec5 \
\cb3           \cf11 \strokec11 data\cf5 \strokec5 .\cf6 \strokec6 boardList\cf5 \strokec5  = \cf6 \strokec6 res\cf5 \strokec5 .\cf6 \strokec6 data\cf5 \cb1 \strokec5 \
\cb3         \})\cb1 \
\cb3     \}\cb1 \
\cb3     \cf6 \strokec6 console\cf5 \strokec5 .\cf10 \strokec10 log\cf5 \strokec5 (\cf10 \strokec10 getList\cf5 \strokec5 ())\cf12 \strokec12 // undefined\cf5 \cb1 \strokec5 \
\cb3     \cf9 \strokec9 return\cf5 \strokec5  \{\cb1 \
\cb3       \cf6 \strokec6 data:\cf5 \strokec5  \cf11 \strokec11 data\cf5 \strokec5 ,\cb1 \
\cb3       \cf10 \strokec10 getList\cf6 \strokec6 :\cf5 \strokec5  \cf10 \strokec10 getList\cf5 \cb1 \strokec5 \
\cb3     \}\cb1 \
\cb3   \}\cb1 \
\cb3 \}\cb1 \
\pard\pardeftab720\sl360\partightenfactor0
\cf2 \cb3 \strokec2 </\cf4 \strokec4 script\cf2 \strokec2 >\cf5 \cb1 \strokec5 \
\
\cf2 \cb3 \strokec2 <\cf4 \strokec4 style\cf2 \strokec2 >\cf5 \cb1 \strokec5 \
\pard\pardeftab720\sl360\partightenfactor0
\cf9 \cb3 \strokec9 @import\cf5 \strokec5  \cf7 \strokec7 'https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css'\cf5 \cb1 \strokec5 \
\pard\pardeftab720\sl360\partightenfactor0
\cf5 \cb3 </style>\cb1 \
\
}