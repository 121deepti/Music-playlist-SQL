# Music-playlist-SQL

<img width="594" alt="schema_diagram" src="https://github.com/121deepti/Music-playlist-SQL/assets/127064830/765e2c15-a349-436e-ae54-836f121c17c6">
There are total 11 tables in the data set connected together.<BR>
The <B>customer table</B> has information regarding customers as well as support_rep_id is the foreign key of this table that connects it with the employee table and has a primary key customer id and it is connected with invoice table.<BR>
The <b>emploee table </b> has inforamtion related to music company's employee where employee id is the primary key.<br>
The <b>invoice table </b> has billing details and has a primary key invoice id<br>
The <b> invoice_line </b> has order details with invoice_line_id is the primary key<br>
The <b>track table</b>keeps the inforamtion related to ordered track details with track_id is the primary key<br>
There are tables like <b>playlist, playlist_track, artist, album, genre and media type</b> that conatins specific details of that track details.<br>


