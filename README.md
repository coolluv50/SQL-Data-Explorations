# SQL-Data-Explorations
This project examines a case study for trades and companies where T-sql query is required for a report based on certain business requirements.
-- Inserting values into both tables to verify correctness of query --
insert into companies values ('Alice s.p.', 'Wonderland');

insert into companies values ('Y-zap', 'Wonderland');

insert into companies values ('Absolute', 'Mathlands');

insert into companies values ('Arcus t.g.', 'Mathlands');

insert into companies values ('Lil Mermaid', 'Underwater Kingdom');

insert into companies values ('None at all', 'Nothingland');

insert into trades values (20121107, 'Lil Mermaid', 'Alice s.p.', 10);

insert into trades values (20123112, 'Arcus t.g.', 'Y-zap', 30);

insert into trades values (20120125, 'Alice s.p.', 'Arcus t.g.', 100);

insert into trades values (20120216, 'Lil Mermaid', 'Absolute', 30);

insert into trades values (20120217, 'Lil Mermaid', 'Absolute', 50
