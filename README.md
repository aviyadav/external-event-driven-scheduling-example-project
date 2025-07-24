# external-event-driven-scheduling-example-project


https://www.youtube.com/watch?v=KgEGrKbfBbM
https://github.com/astronomer/external-event-driven-scheduling-example-project

Astro CLI
https://www.astronomer.io/docs/astro/cli/install-cli/?tab=windowswithwinget#install-the-astro-cli

create project

	astro dev init
	copy docker-compose.override.yml from https://github.com/astronomer/external-event-driven-scheduling-example-project
	uv venv
	uv pip install apache-airflow
	uv pip install apache-airflow-providers-apache-kafka apache-airflow-providers-common-messaging
	astro dev start
