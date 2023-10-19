# {{ cookiecutter.project_name }}

This happens when you try to use the cookiecutter variable for top level directory.

Please check the directory structure, it should be like this:

my_repo_name
      - cookiecutter.json
      - {{cookiecutter.data_directory}}
            - filea.txt
      - {{cookiecutter.some_file}}.py
