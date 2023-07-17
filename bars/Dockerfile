FROM python:3.9
COPY requirements.txt /
COPY index.py /
RUN pip install -r requirements.txt
EXPOSE 8050
CMD ["python", "-u", "index.py"]