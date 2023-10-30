# xanim.html
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>YAZILIM KODLAMA</title>
</head>
<body style="background-color: WhiteSmoke;">
 
    <form>
        <fieldset>
            <legend>
                iletişim Formu
            </legend>
        
        
        <table border="1">
            
            <tr>
                <td>Adınız Soyadınız : </td>
                <td><input type="text" name="adsoyad"> </td>
            </tr>
            <tr>
                <td>E-Posta Adresiniz : </td>
                <td><input type="text" name="mail"> </td>
            </tr>
            <tr>
                <td>Telefonunuz : </td>
                <td><input type="text" name="mail" placeholder="(___)(_______)"> </td>
            </tr> 
            
            <tr>
                <td>TC Kimlik Numaranız : </td>
                <td><input type="text" name="tckimlik" placeholder="11 hane olmalıdır."> </td>
            </tr>
            
            <tr>
                <td>Bildiğiniz Yabancı Diller</td>
                <td>
                <label for="ing">İngilizce</label><input type="checkbox" id="ing" value="ing"><br>
                <label for="alm">Almanca</label><input type="checkbox" id="alm" value="alm"><br>
                <label for="fra">Fransızca</label><input type="checkbox" id="fra" value="fra">
                </td>
            </tr>
            
            <tr>
                <td>Mesajınız : </td>
                <td><textarea cols="22" rows="7" name="mesaj"></textarea> </td>
            </tr>
        
        </table>
        
        </fieldset>
        
    </form>
    
</body>
</html>
