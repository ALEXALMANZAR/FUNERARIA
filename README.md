<!DOCTYPE html>
<html lang="en">
<head>

    <title>DATOS INSCRICION</title>
    <style>
        body {color: green;}
    </style>
</head>
<body> 
    <CENTER>
    <h1>FUNERARIA LA ESPERANZA DEL DESCANSO</h1>
    <h2>Oficinas en San Juan de la Maguana:</h2>
       <h3>
        1.- Ave. Circunvalación Sur, Edif. 3 #102,<br>
         próximo a la Ferretería Aquino, casi esq. Calle Eusebio Puello
        <br>
        2.- Carretera a Jínova #210    
        <br>
        Tel.: 809-344-1836 / Cel.: 829-759-1812
        <br>
        <h2> Santo Domingo:</h2>
        <h3>
        Calle 5 #75B, Barrio Juana Saltitopa, Los Alcarrizos, Sto. Dgo. Oeste, R. D.
        <br>
        Tel.: 809-473-0715   Cel.: 809-409-2384
        </h3>
    <h2>FORMULARIO DE SOLICITUD DE INSCRIPCIÓN</h2>

    <form action="/C:\Users\SAONI ROMERO\Desktop\PROGRAMAS\DATOS/" method="get">
        <b>
        <!-- Entry Date -->
        <label for="FECHA DE INGRESO">FECHA DE INGRESO:</label>
        <input type="date" id="FECHA DE INGRESO" name="FECHA DE INGRESO" required> <label for="CONTRATO NO.">CONTRATO NO.:</label>
        <input type="number" id="CONTRATO NO." name="CONTRATO NO." required>

        <label for="PLAN">PLAN:</label>
        <select id="PLAN" name="PLAN" required>
            <option value="planA">Plan A</option>
            <option value="planB">Plan B</option>
            <option value="planC">Plan C</option>
            <!-- Add more options as needed -->
        </select>

        <!-- Installments -->
        <label for="CUOTAS">CUOTAS RD$:</label>
        <input type="number" id="CUOTAS" name="CUOTAS" required style="width: 50px;"><br>

        <br>      

        <label for="nombre">NOMBRE:</label>
        <input type="text" id="nombre" placeholder="NOMBRE" style="width: 200px;">
        
        <label for="APELLIDO"> APELLIDO:</label>
        <input type="text" id="APELLIDO" placeholder="APELLIDO" style="width: 200px;">
        
        <label for="APODO"> APODO:</label>
        <input type="text" id="APODO" placeholder="APODO" style="width: 200px;">

        <label for="EDAD"> EDAD:</label>
        <input type="number" id="EDAD" placeholder="EDAD" style="width: 40px;">

        <label for="CEDULA"> CEDULA:</label>
        <input type="text" id="CEDULA" placeholder="CEDULA" style="width: 150px;"><br><br>
        
        <label for="CEDULA"> FOTO DE CEDULA:</label>
        <input type="file" id="CEDULA" placeholder="CEDULA" style="width: 150px;">

        <label for="CASA"> FOTO DE LA CASA:</label>
        <input type="file" id="CEDULA" style="width: 150px;"> <input type="file" id="CEDULA" style="width: 150px;">

        <label for="NACIONALIDAD"> NACIONALIDAD:</label>
        <input type="text" id="NACIONALIDAD" placeholder="NACIONALIDAD" name="NACIONALIDAD" required><br><br>

        <label for="contractorDOB"> FECHA DE NACIMIENTO:</label>
        <input type="date" id="contractorDOB" name="contractorDOB" required>

        <label for="CALLE Y NO">CALLE Y NO:</label>
        <input type="text" id="CALLE Y NO" placeholder="CALLE Y NO" style="width: 600px;"><br><br>

        <label for="ZONA">ZONA:</label>
        <input type="text" id="ZONA" placeholder="ZONA" style="width: 200px;">
        
        <label for="SECTOR"> SECTOR:</label>
        <input type="text" id="SECTOR" placeholder="SECTOR" style="width: 200px;">
        
        <label for="REFERENCIA"> REFERENCIA:</label>
        <input type="text" id="REFERENCIA" placeholder="REFERENCIA" style="width: 500px;"><br><br>

        <label for="TELEFONO">TELEFONO1:</label>
        <input type="tel" id="TELEFONO" placeholder="ejemplo (809)-555-5555" name="TELEFONO">

        <label for="TELEFONO2">TELEFONO2:</label>
        <input type="tel" id="TELEFONO2" placeholder="ejemplo (809)-555-5555" name="TELEFONO2">

        <label for="CELULAR">CELULAR:</label>
        <input type="tel" id="CELULAR" placeholder="ejemplo (809)-555-5555" name="CELULAR" required>

        <!-- Member Information (Repeat as needed) -->
        <h2>BENEFICIARIOS DEL PLAN</h2>

        <!-- Member 1 -->
        <label for="member1">1:</label>
        <input type="text" id="name" style="width: 500px;"> PARENTESCO:<input type="text" id="name" placeholder="ejemplo: padre, madre, hijo/a" style="width: 150px;"><label for="age1"> EDAD:</label>
        <input value="0" type="text" id="age1" name="age1" required><br><br>
        
        <label for="member1">2:</label>
        <input type="text" id="name" style="width: 500px;"> PARENTESCO:<input type="text" id="name" style="width: 150px;"><label for="age1"> EDAD:</label>
        <input value="0" type="text" id="age2" name="age2" required><br><br>

        <label for="member1">3:</label>
        <input type="text" id="name" style="width: 500px;"> PARENTESCO:<input type="text" id="name" style="width: 150px;"><label for="age1"> EDAD:</label>
        <input value="0" type="text" id="age3" name="age4" required><br><br>

        <label for="member1">4:</label>
        <input type="text" id="name" style="width: 500px;"> PARENTESCO:<input type="text" id="name" style="width: 150px;"><label for="age1"> EDAD:</label>
        <input value="0" type="text" id="age4" name="age4" required><br><br>

        <label for="member1">5:</label>
        <input type="text" id="name" style="width: 500px;"> PARENTESCO:<input type="text" id="name" style="width: 150px;"><label for="age1"> EDAD:</label>
        <input value="0" type="text" id="age5" name="age5" required><br><br>

        <label for="member1">6:</label>
        <input type="text" id="name" style="width: 500px;"> PARENTESCO:<input type="text" id="name" style="width: 150px;"><label for="age1"> EDAD:</label>
        <input value="0" type="text" id="age6" name="age6" required><br><br>

        <label for="member1">7:</label>
        <input type="text" id="name" style="width: 500px;"> PARENTESCO:<input type="text" id="name" style="width: 150px;"><label for="age1"> EDAD:</label>
        <input value="0" type="text" id="age7" name="age7" required><br><br>

        <label for="member1">8:</label>
        <input type="text" id="name" style="width: 500px;"> PARENTESCO:<input type="text" id="name" style="width: 150px;"><label for="age1"> EDAD:</label>
        <input value="0" type="text" id="age8" name="age8" required><br><br>

        <label for="member1">9:</label>
        <input type="text" id="name" style="width: 500px;"> PARENTESCO:<input type="text" id="name" style="width: 150px;"><label for="age1"> EDAD:</label>
        <input value="0" type="text" id="age9" name="age9" required><br><br>

        <label for="member1">10:</label>
        <input type="text"id="name" style="width: 500px;"> PARENTESCO:<input type="text" id="name" style="width: 150px;"><label for="age1"> EDAD:</label>
        <input value="0" type="text" id="age10" name="age10" required><br><br><br><br>

        <label for="DIRECCIÓN GPS">DIRECCÓN GPS:</label>
        <input type="text" id="name" placeholder="PEGAR LINK GPS AQUI" style="width: 500px;">
        <br><br>

        <label for="CASA">  FOTO DE LA CASA:</label>
        <input type="file" id="CASA" placeholder="CASA" style="width: 150px;"><br><br>

        <label for="CASA"> FOTO DE LA CALLE:</label>
        <input type="file" id="CASA" placeholder="CASA" style="width: 150px;"><br><br><br>

        <a href="#FECHA DE INGRESO"> ir al inicio </a><br><br>
        

        <!-- Repeat the above block for each additional member -->

        <!-- Submit Button -->
        <input style="color: green;" type="submit" value="ENVIAR"><br><br><br><br><br>

        <a target="_blank" href="https://maps.google.com/maps?q=18.7977515%2C-71.2325148&z=17&hl=es"> NUESTRA UBICACIÓN</a><br>
    </b>
    </form>
    </CENTER>

</body>
</html>
