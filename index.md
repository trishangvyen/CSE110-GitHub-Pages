# Trisha Nguyen
I am currently a **second year** at _Sixth College_ majoring in <ins>Computer Science</ins>.
![Photo of me](/assets/images/IMG_8330.jpg)
> I <3 UCSD!

## My Code
Here's some code I have written last quarter in my project class:
```
#Mentor register
@router.post('/mentor/register', response_model=DataResponse[MentorItemResponse])
def register_mentor(register_data: MentorCreate, mentor_service: MentorService = Depends()):
    mentor = mentor_service.register_mentor(register_data)
    return DataResponse().success_response(data=mentor)
```
My LinkedIn page can be found [here](www.linkedin.com/in/trisha-nguyen-658538202)

## Other Things
If you're looking for my code or LinkedIn, you can find it in the section [above](#my-code)\
The readme file can be found right [here](README.md)\
Some of my hobbies are:
- Gaming
- Going out
- Raving and concerts
- Eating good food and drinks\
The top 3 concerts/raves I've been to are:
1. NCT Dream TDS2
2. Escape Halloween 2024
3. Twice 3rd World Tour Encore

## Task List
Some of my goals are:
- [x] Go to lecture this quarter!!
- [ ] Graduate with at least a 3.6 GPA
- [ ] Get a job this summer
- [ ] Find an apartment