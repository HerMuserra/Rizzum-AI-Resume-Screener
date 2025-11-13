# Rizzumé – AI Resume Screener 🔍

**Description:**  
Upload a resume and a job description, and let **Rizzumé** do the magic ✨.  
It calculates how well the resume matches the job using keyword similarity and gives a match score (%) instantly. Perfect for AI demos, learning projects, or flexing your coding chops.

## Files
- `resume_matcher.py` → main Python code  
- `resume.txt` → example resume  
- `job_description.txt` → example job description  
- `requirements.txt` → dependencies (`nltk`, `scikit-learn`)  
- `LICENSE` → MIT License

## Install dependencies
```bash```
pip install -r requirements.txt


##Run Rizzumé
bash
python resume_matcher.py


The program will read resume.txt and job_description.txt
It will print the match score like:

Rizzumé Match Score: 87.65%

How to customize
Replace resume.txt with your own resume

Replace job_description.txt with the job description you want to match

Run the script again to get the new match score
