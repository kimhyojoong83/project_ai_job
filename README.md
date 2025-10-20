25-10-20 주제 선정 및 데이터 시각화, 전처리
columns : ['job_id' 'company_name', 'industry', 'job_title', 'skills_required', 'experience_level', 'employment_type', 'location', 'salary_range_usd', 'posted_date', 'company_size', 'tools_preferred']
use_cols = ['industry', 'job_title', 'skills_required', 'experience_level', 'employment_type', 'location', 'salary_range_usd', 'posted_date', 'company_size', 'tools_preferred']

experience_level(경력 여부)
Entry(신입): 0, Mid(경력): 1, Senior(시니어): 3

employment_type
Contract(계약직): 0, Remote(프리렌서): 1, Internship(인턴십): 2, , Full-time(정규직): 3

company_size
Startup(스타트업): 0, Mid(중소기업): 1, Large(대기업): 2
