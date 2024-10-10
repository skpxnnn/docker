FROM ubuntu:latest

# ติดตั้ง bash
RUN apt-get update && apt-get install -y bash

# คัดลอกไฟล์ script.sh ไปยัง container
COPY script.sh /

# รัน script.sh โดยใช้ bash
CMD ["bash", "/script.sh"]



