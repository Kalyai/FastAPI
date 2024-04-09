# FastAPI
**Author: Sergei Kalyaev**  
Project for create and download database

## Description
I used:  
- from fastapi import FastAPI, APIRouter, Depends
- from contextlib import asynccontextmanager
- from sqlalchemy import select
- from typing import Annotated, Optional
- from pydantic import BaseModel, ConfigDict
- from sqlalchemy.ext.asyncio import create_async_engine, async_sessionmaker
- from sqlalchemy.orm import DeclarativeBase, Mapped, mapped_column

router to get and add database  
sqlalchemy (DeclarativeBase) to create and delete tables  
repository.py for get tables from database  
lifespan and general main.py for run web app  
schemas.py for simplifications and comfort  

## To run it  
- git clone `url repository`
- pip install FastAPI uvicorn sqlalchemy aiosqlite greenlet
- cd FastAPI
- uvicorn main:app

## Technology Stack  
- ![Python](https://img.shields.io/badge/-Python-blue?style=flat-square&logo=python)  
- ![FastAPI](https://img.shields.io/badge/-FastAPI-green?style=flat-square&logo=fastapi)  
- ![SQLAlchemy](https://img.shields.io/badge/-SQLAlchemy-blue?style=flat-square&logo=sqlalchemy)  


## Screenshots  
<img src="screenshots/scr1.png" alt="Screenshot" width="400" height="200">  
<img src="screenshots/scr3.png" alt="Screenshot" width="400" height="200">   
<img src="screenshots/scr2.png" alt="Screenshot" width="400" height="200">  
