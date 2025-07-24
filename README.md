# external-event-driven-scheduling-example-project


https://www.youtube.com/watch?v=KgEGrKbfBbM
<br>
https://github.com/astronomer/external-event-driven-scheduling-example-project

Astro CLI
<br>
https://www.astronomer.io/docs/astro/cli/install-cli/?tab=windowswithwinget#install-the-astro-cli

create project

	astro dev init
<br>
	copy docker-compose.override.yml from https://github.com/astronomer/external-event-driven-scheduling-example-project
<br>
	uv venv
<br>
	uv pip install apache-airflow
<br>
	uv pip install apache-airflow-providers-apache-kafka apache-airflow-providers-common-messaging
<br>
	astro dev start
<br>
