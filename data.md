# roles <enum>
- admin
- project leader
- project member

# project status <enum>
- active
- archived
- finished

# priority <enum>
- low
- medium
- high

# member
- id
- name
- email

# task
- id
- name
- description
- start date <date>
- end date <date>
- status <enum>
- task members <list[member]>
- priority <enum>
- notes <list[str]>

# project
- id
- name
- description
- config
    - log dates <bool>
- start date <date>
- deadline <date>
- status <enum>
- project leader <member>
- project members <list[member]>
- tasks <list[task]>
- priority <enum>
- notes <list[str]>
