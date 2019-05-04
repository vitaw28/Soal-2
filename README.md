# Soal-2
Software yang dibutuhkan: Visual Code Studio, Chrome

/* Membuat username dan password*/

<body>
    <form onSubmit="alert('Submitted.');return false;">
        <input type="text" title="8 Character Username"
        pattern="^[a -z]" placeholder="Username" required />
        <input type="password" title="minimum 8 Character Pasword. 
        Use Lowercase, UpperCase, Numeric, and Special Character" 
        pattern="(?=^.{8,}$)((?=.*\d)|(?=.8\W+))(?![.\n]
        (?=.*[A -Z]) (?=.*[a -z]).*$" placeholder="Password" 
        required/>
        <input type="submit" value="Login"/>
    </form>
</body>
