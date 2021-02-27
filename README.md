# Trashmaster Knowledge Graph Lab <!-- omit in toc -->

- [Problem statements](#problem-statements)
- [Play](#play)
  - [Choose your environment](#choose-your-environment)
  - [Run](#run)
- [Data model](#data-model)
- [User stories](#user-stories)
  - [Trash Epic](#trash-epic)
  - [Admin Epic](#admin-epic)

[Trashmaster](https://trashmaster.be) Knowledge Graph lab

![kg](./docs/assets/kg-trash-map.jpg)

Our mission is to help the different actors to optimize their deployments regarding to the streets cleaning.

## Problem statements

- Illegal trash dumping predication: **WHEN** and **WHERE** will be dumped to most trashes.
- Route optimization: finding the shortest path to pick-up the trashes.

## Play

### Choose your environment

* [Oracle](./infra/oracle/docker-compose.yml)
* [Postgre](./infra/postgre/docker-compose.yml)

### Run

`docker-compose up`

**Coming soon**
- Data generation
- Jupyter
- https://age.apache.org

## Data model

[Here](./docs/data-model.md)

## User stories

### Trash Epic
TE-S1: As a User, I want to create a new Trash, so that I can get my Trash coins.
TE-S2: As a User, I want to confirm and emphasise a created trash, so that I can get my Trash coins.
TE-S3: As a User, I want to mark a created Trash as cleaned Trash, so that I can get my Trash coins.
TE-S4: As a User, I want to mark a cleaned Trash as dirty Trash, so that I can get my Trash coins.
TE-S5: As a User, I want to confirm and emphasise a cleaned Trash, so that I can get my Trash coins.
TE-S6: As a User, I want to know more details about the trash, so that I can take decisions about it.
TE-S7: As a User, I want to indicate that a trash is dangerous, so that the next users will know it.

### Admin Epic
AE-S1: As an admin, I want to have a big picture view on trash locations, so that we can take decisions regarding to the cleaning rounds.
AE-S2: As an admin, I want to know where we could find trashes in the future, so that I can anticipate and optimize the cleaning rounds even if we don't have enough weekly data. (not very useful, just for fun)
AE-S3: As an admin, I want to have the shortest path to clean the trashes, so that we can save precious time during the cleaning rounds.
