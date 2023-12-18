<h1>Creació d'una taula a Mariadb</h1>

# mysql -u root -p
<p> Primer de tot hem d'entrar al Mariadb </p>

 <p> CREATE TABLE coches (
    matricula VARCHAR(10) PRIMARY KEY,
    marca VARCHAR(50),
    nombre_del_coche VARCHAR(50),
    km_recorridos INT
);</p>

<p> Aqui li hem de posar els atributs a la base de dades assignant la matricula com a clau primaria </p>


<p>SELECT * FROM coches;
    NSERT INTO coches (matricula, marca, nombre_del_coche, km_recorridos) VALUES
('ABC123', 'Toyota', 'Corolla', 50000),
('XYZ789', 'Honda', 'Civic', 60000);</p>

# SELECT * FROM coches;

<p>  </p>

