# GitHub
SELECT * FROM "LOCALIDADES";
SELECT * FROM "COMUNIDADES";
SELECT * FROM "Provincias";
SELECT DISTINCT "NOMBRE", "POBLACION"FROM "LOCALIDADES", "COMUNIDADES" WHERE "ID_LOCALIDAD"=160;
SELECT sum("POBLACION") from "LOCALIDADES", "COMUNIDADES" where "ID_COMUNIDAD"=1;
