# UTS-Pengenalan-Big-Data
<center> <image src='logo-akakom.png'> </center>
<h3>1. Cari dan sebutkan 3 DBMS yang bisa digunakan untuk mengelola big data</h3>
berdasarkan tipe <br>
    • key value : Riak, Redis, Couchbase, Dynamodb <br>
    • document : Apache CouchDB, ArangoDB, BaseX, Clusterpoint <br>
    • graph : Neo4J, OrientDB, Virtuoso <br>
    • kolom : Cassandra, Scylla, Apache Druid, HBase<br>
<image src='dbnosql.png'>    
<div>
   <h3>2. Carilah contoh masalah big data yang bisa dikelola menggunakan salah satu DBMS tersebut, jelaskan mulai dari instalasi sampai CRUD untuk data menggunakan DBMS tersebut. Asumsikan anda akan memecahkan masalah big data yang sudah anda cari contoh tadi, jelaskan kira-kira bagaimana arsitektur dari solusi big data menggunakan DBMS tersebut, gambarkan diagramnya</h3> 
CASSANDRA <br>
INSTALASI<br>
1. cek java dan jdk apakah sudah terinstall<br>
<image src='java_version.png'>  
<br>2. Download package dan ekstrak
<image src='down-cass.png'>  
<br>3.  Menambahkan repository cassandra ke `etc/apt/sources.list.d/cassandra/sources.list`<br>
`echo "deb https://downloads.apache.org/cassandra/debian 311x main" | sudo tee -a /etc/apt/sources.list.d/cassandra.sources.list`
 
<br>4. menambahkan key repository
<image src='execue-key.png'>  
<br>5. Menambahkan public key
<image src='cass-key.png'>  
<br>6. Install Cassandra
<image src='insall-cass.png'>  
<br>7.  Selesai
 untuk menjalankan cassandra `sudo service cassandra start` untuk berhenti `sudo service cassandra stop`. 

</div>


<div> 
CRUD CASSANDRA Dalam akademik<br>
1. menjalankan cql<br>
<image src='cqlsh.png'><br>  
2. membuat keyspace akademik<br>
<image src='create-keyspace.png'>  <br>
3. menggunakan keyspace akademik dan membuat table mahasiswa (create)<br>
<image src='create-table.png'>  <br>
4. menginput data/insert into table mahasiswa (create)<br>
<image src='insert-into-all.png'>  <br>
5. membaca isi table (read)<br>
<image src='show.png'> <br> 
6. mengupdate data (update)<br>
<image src='update.png'> <br> 
7. menghapus data(delete)<br>
`Delete bekerja from akademik.mahasiswa Where nim=185410172;` 

</div>

note
