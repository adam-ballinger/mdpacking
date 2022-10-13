# MD Packing
MD packing web application.

## Author
Adam Ballinger

## Models

1. Processor
- _id: ObjectID (Unique identifier)
- name: String (First and last name)
- packs: Int32 (Number of career packs)

2. Pack
- _id: ObjectID
- lpn: String
- time: String
- date: String
- processor: String

## Views

1. Packing
- Processors scan LPN's to upload packs to database and displays information of last scan.

2. Packs
- Processors and supervisors view a list of packs completed.

3. Processors
- Supervisors can view and add processors.

## Routes

- GET: /packs
- POST: /packs
- GET: /processors
- GET: /processors/:id
- POST: /processors
- POST: /processors/:id