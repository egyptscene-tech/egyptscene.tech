| database server |                reason                |
|:---------------:|:------------------------------------:|
|    postgresql   | will allow analytics team to use DBT |

### Tables
**user**
- id: will be used in analytics
- email
- gender
- first_job_date
- real_exp_in_years

**title: will be filled by admin**
- id
- title: [frontend, backend, ...]

**seniority_level: will be filled by admin**
- id
- seniority_level: [junior, med, ...]

**city: will be filled by admin**
- id
- name: [cairo, giza, ...]

**feeling: will be filled by admin**
- id
- feel: [overrated, normal, underrated]

**skill**
- id
- name
- is_theoretical_skill: [means theoretical, or technical skill]

**skill_level**
- id
- level: [1 to 3]
- description: the skill level have to be described in sentence
  - 1: watched some tutorials, and know how to work with some help
  - 2: watched a lot of tutorials, and solve most of my problem so myself
  - 3: solve other people problems

**company**
- id
- name
- linkedin
- website

**job_history**
- id
- user_id
- title_id
- seniority_level_id
- city_id
- is_remote
- feeling_id
- start_date
- end_date
- salary
- open_to_work: in case of current job

**job_history_skill**
- job_history_id
- skill_id
- skill_level_id
