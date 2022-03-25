# first


1.Initialize table data
w ##Class(SCHOOL.Api).Api("InitSutdentInfo").%ToJSON()	

2.Check the students' scores
w ##Class(SCHOOL.Api).Api("QueryStuSubj", "{""student"":"""",""subject"":""""}").%ToJSON()

3.Modify student scores
w ##Class(SCHOOL.Api).Api("UpdateScore", "{""student"":""student6"",""subject"":""art"",""score"":""99""}").%ToJSON()

4.Check the students' scores
w ##Class(SCHOOL.Api).Api("QueryStuSubj", "{""student"":""student6"",""subject"":""art""}").%ToJSON()

5.Students' scores ranking
w ##Class(SCHOOL.Api).Api("SortByScore", "{""subject"":""art"",""passScore"":""60"",""order"":""1""}").%ToJSON()



first
