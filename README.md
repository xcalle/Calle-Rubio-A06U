<h1>Creació d'una taula a Mariadb</h1>

<h2> mysql -u root -p</h2>
<p> Primer de tot hem d'entrar al Mariadb </p>


 <h2> CREATE TABLE coches (

    matricula VARCHAR(10) PRIMARY KEY,
    marca VARCHAR(50),
    nombre_del_coche VARCHAR(50),
    km_recorridos INT

);</h2>

<p> Aqui li hem de posar els atributs a la base de dades assignant la matricula com a clau primaria </p>


<h2>SELECT * FROM coches;
    NSERT INTO coches (matricula, marca, nombre_del_coche, km_recorridos) VALUES
('ABC123', 'Toyota', 'Corolla', 50000),
('XYZ789', 'Honda', 'Civic', 60000);</h2>


<p> Aqui hem d'indicar el l'informació del cotxe matricula, marca, nom_del_cotxe, km_recorreguts </p>







