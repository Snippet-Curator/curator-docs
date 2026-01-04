---
title: Install
description:
---

Install Curator with Docker compose:

<pre><code>
services:
  pocketbase:
    image: kangruixiang/pocketbase:latest
    volumes:
      - ./pb_data:/app/db/pb_data # data base folder
    ports:
      - "8090:8090"

  curator:
    image: kangruixiang/curator:latest
    environment: 
      - PUBLIC_POCKETBASE_URL=http://localhost:8090 # change this to your actual server URL 
      - PUBLIC_INTERNAL_POCKETBASE_URL=http://pocketbase:8090
    depends_on: 
      - pocketbase
    ports: 
      - "3000:3000"
</code>
</pre>
