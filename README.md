# Hi, That's me!
- > [Linkedin](https://www.linkedin.com/in/eniseirem/) [Medium](https://medium.com/me/design)
> I've a sticker which says "Talk is cheap show me the code." 
> So here I am, showing you **The Code**. 

```python
import educations as e
import jobs as j

# A simple class to learn about the person
class eniseirem:
     name = "Enise İrem Çolak"
     title = "Software Engineer"
     location = "Istanbul"
     age = 23
     
      # You can directly open my linkedin for more info. 
      
     def get_linkedin(self):
          return "https://www.linkedin.com/in/eniseirem/"
   
     def get_current_job(self):
          jobs = j.all()
          jobs = jobs.sort_values("timestamps")          
          return jobs[-1] ## Kapital Medya, Software Developer        
          
     def get_education(self):
          if(e.degree=="Bachelor's"):
               e.university("Bahcesehir University")
               e.departmant("Software Engineering")
               e.graduate(True)
               e.year(2015,2019)
               
          elif(e.degree=="Master's"):
               e.university("Bahcesehir University")
               e.departmant("Big Data")
               e.graduate(False)
               e.year(2019,2022)
               
          else:
               return "wdy need mate?"
               
           return e.educations()
           

     def get_knowledge(self):
          
          knowledge["frameworks"]            =    {PHP  :  "Laravel",
                                                  Python:  "Django"}
                                             
          knowledge["programming_languages"] =  { "Python" : "data science main",
                                                  "PHP"    : "Current job",    
                                                  "R"      : "data science basic knowledge",
                                                  "Matlab" : "School needs it sometimes",
                                                  "Java"   : "used in bachelors",
                                                  "C#"     : "used in bachelors2",
                                                  "Julia"  : "Personal curiosity, learning"}
          knowledge["other_technologies"]    = [GNU/Linux, MySQL, Weka]
                                                  
          knowledge["languages"]             =  {  Turkish : "Native",
                                                   English : "Professional",
                                                   Italian :  "A1"          
                                                  }
          
          return knowledge

```
