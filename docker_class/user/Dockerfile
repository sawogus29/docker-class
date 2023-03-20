FROM ubuntu
RUN mkdir -m 1777 /share \
&& touch /share/hello.txt \
&& useradd student

USER student
RUN touch /share/student.txt
CMD ls -l /share
