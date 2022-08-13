# Pull the base image
FROM tiangolo/uwsgi-nginx-flask:python3.6
# Install depndencies 
RUN pip install redis==3.5.3
RUN pip install opencensus==0.7.13
RUN pip install opencensus-ext-azure==1.0.4
RUN pip install opencensus-ext-flask==0.7.3
RUN pip install opencensus-ext-logging==0.1.0
RUN pip install Flask==1.1.2
RUN pip install jinja2==3.0.3
RUN pip install werkzeug==2.0.3
RUN pip install itsdangerous==2.0.1

# Copy the content of the current directory to the /app of the container
ADD . /app
