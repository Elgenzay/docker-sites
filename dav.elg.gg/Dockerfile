FROM tomsquest/docker-radicale

RUN /venv/bin/pip install --no-cache-dir vobject python-dateutil

COPY radicale-birthday-calendar/create_birthday_calendar.py /usr/local/bin/create_birthday_calendar.py
