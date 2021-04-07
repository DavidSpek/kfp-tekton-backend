FROM python:3.9.4
RUN pip install gcsfs
RUN pip install pandas
COPY ./visualize.py .
CMD ["python", 'visualize.py']