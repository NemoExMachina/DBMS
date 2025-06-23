# Welcome to My Site
<html>
	<head>
		<title>Database Management System</title>
	</head>
	<body style="font-family: Arial, sans-serif; background-color: #f4f4f4; color: #333; margin: 0; padding: 0;">
		<center>
			<h1 style="font-family: fantasy; color: #4CAF50;">Chapter 1: Database Management System</h1>
		</center>
		<table style="border-collapse: collapse; width: 100%; margin: 20px auto; background-color: #fff;">
			<tr>
				<th style="padding: 10px; background-color: #4CAF50; color: white;">Unit</th>
				<th style="padding: 10px; background-color: #4CAF50; color: white;">Contents</th>
			</tr>
			<tr>
				<td style="padding: 10px; border: 1px solid #ddd;">
					<ol>
						<a href="1.html" style="text-decoration: none; color: #333;">
							<li>Database Management System</li>
						</a>
					</ol>
				</td>
				<td style="padding: 10px; border: 1px solid #ddd;">
					<p>1.1 Introduction to data, database, Database Management System, DBMS</p>
					<p>1.2 Field, Record, Objects, Primary Key, Alternate key, Candidate key</p>
					<p>1.3 Advantages of using DBMS</p>
					<p>1.4 DDL(Data Definition Language) and DML(Data Manipulation Language)</p>
					<p>1.5 Database Model: Network Model, Hierarchical Model, Relational database model</p>
					<p>1.6 Concept of Normalization: 1NF, 2NF, 3NF</p>
					<p>1.7 Centralized Vs. Distributed Database</p>
					<p>1.8 Database Security</p>
				</td>
			</tr>
		</table>
	</body>
</html>



<html>
  <head>
    <title>Chapter 1</title>
    <link rel="stylesheet" href="styles.css">
  </head>
  <body>
    <div class="container">
      <h1 class="main-title">Chapter 1: Database Management System</h1>
      
      <h2 class="sub-title">Introduction to Data, Database, and DBMS</h2>
      <p><strong>Data:</strong> Data are the collection of raw facts and figures—unorganized, uninterpreted, and isolated—which don’t provide any specific meaning until processed.</p>
      <p><strong>Example:</strong> Ram, 17, Pokhara, 18</p>

      <p><strong>Information:</strong> Information is the processed form of data that carries meaningful context.</p>
      <p><strong>Example:</strong> Ram is 17 years old and lives in Pokhara-18.</p>

      <h3>Challenges with Traditional File Systems</h3>
      <ul>
        <li>Redundancy due to duplicate data across files</li>
        <li>Difficult data presentation and retrieval</li>
        <li>Poor data security and manipulation speed</li>
      </ul>

      <p>To overcome these, databases were introduced—collections of related data organized in tabular form to support quick access and informed decision-making.</p>

      <h3>Example Table:</h3>
      <table border="1" cellpadding="5" cellspacing="0">
        <tr>
          <th>Roll No</th>
          <th>Name</th>
          <th>Address</th>
          <th>Contact</th>
        </tr>
        <tr>
          <td>1</td>
          <td>Aaishu Karki</td>
          <td>Pokhara</td>
          <td>0090786</td>
        </tr>
        <tr>
          <td>2</td>
          <td>Bishaka Lohani</td>
          <td>Bhairab Tole</td>
          <td>3452423</td>
        </tr>
      </table>
      <p><em>Note: A column is called a “field” and a row is called a “record.”</em></p>

      <h2 class="sub-title">What is a DBMS?</h2>
      <p>A Database Management System (DBMS) is a software suite that defines, manipulates, and manages databases. It enables users to efficiently retrieve, update, and manage data.</p>
      <p><strong>Examples:</strong> MS Access, Oracle, MySQL, FoxPro, DBase</p>

      <h3>Advantages of DBMS:</h3>
      <ul>
        <li>Shared access across multiple users and devices</li>
        <li>Reduces data redundancy</li>
        <li>Allows for data backup and recovery</li>
        <li>Provides data security and controlled access</li>
        <li>Supports multiple user interfaces</li>
        <li>Ensures data integrity</li>
      </ul>

      <h3>Disadvantages of DBMS:</h3>
      <ul>
        <li>High operational costs</li>
        <li>Requires trained personnel and regular updates</li>
        <li>Regular backups are essential</li>
      </ul>
<div class="container">
  <!-- Existing content... -->

  <h2 class="sub-title">Distributed vs. Centralized Databases</h2>
  <h3>Distributed Database</h3>
  <p>Distributed databases store data across multiple servers located in different geographical areas. They’re ideal for large organizations needing high-speed access and robust recovery across global networks.</p>
  <h4>Advantages:</h4>
  <ul>
    <li>Improved backup and recovery</li>
    <li>Handles large-scale data and users</li>
    <li>Better bandwidth utilization</li>
  </ul>
  <h4>Disadvantages:</h4>
  <ul>
    <li>Expensive to maintain</li>
    <li>Potential security concerns</li>
  </ul>

  <h4>Comparison Table</h4>
  <table border="1" cellpadding="5" cellspacing="0">
    <tr><th>Centralized</th><th>Distributed</th></tr>
    <tr><td>Simple type</td><td>Complex type</td></tr>
    <tr><td>Located at a single point</td><td>Spread across locations</td></tr>
    <tr><td>One server</td><td>Multiple servers</td></tr>
    <tr><td>Easy maintenance</td><td>Hard to maintain</td></tr>
    <tr><td>High security</td><td>Lower security</td></tr>
    <tr><td>Low cost</td><td>Expensive</td></tr>
  </table>

  <h2 class="sub-title">Structured Query Language (SQL)</h2>
  <p>SQL is a standard language developed by IBM in the 1970s to communicate with relational databases. It includes:</p>
  <ul>
    <li><strong>DDL</strong> – To define structure (e.g., CREATE TABLE)</li>
    <li><strong>DML</strong> – To manipulate data (e.g., INSERT, SELECT)</li>
    <li><strong>DCL</strong> – To control access (e.g., GRANT)</li>
  </ul>

  <h2 class="sub-title">Entity Relationship Model</h2>
  <p>The ER model describes real-world entities and their relationships graphically. Components include:</p>
  <ul>
    <li><strong>Entity</strong>: Real-world object, shown as rectangles</li>
    <li><strong>Attributes</strong>: Properties, shown as ovals</li>
    <li><strong>Relationships</strong>: Associations, shown as diamonds</li>
  </ul>

  <h2 class="sub-title">Database Administrator (DBA)</h2>
  <p>The DBA maintains the database, assigns roles, manages security, backups, and user training. A DBA must understand DBMS tools, operating systems, and networking.</p>

  <h2 class="sub-title">Normalization</h2>
  <p>Normalization is the process of structuring databases to reduce redundancy using normal forms (1NF, 2NF, 3NF). It improves database efficiency and clarity.</p>
  <h4>Normal Forms:</h4>
  <ul>
    <li><strong>1NF</strong>: Remove duplicate columns, use primary keys</li>
    <li><strong>2NF</strong>: Remove partial dependencies</li>
    <li><strong>3NF</strong>: Remove transitive dependencies</li>
  </ul>

  <p>Example tables were progressively decomposed from unnormalized to 3NF to improve structure and eliminate data duplication.</p>
</div>

    </div>
  </body>
</html>

