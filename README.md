<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>رأيك في الموقع</title>
  </head>
  <body>
    <h1>رأيك في الموقع</h1>
    <form action="#" method="post">
      <label for="prenom">الإسم:</label>
      <input type="text" id="prenom" name="prenom" required /> <br /><br />
      <label for="nom">اللقب:</label>
      <input type="text" id="nom" name="nom" required /><br /><br />
      <label for="date de naissance">تاريخ الميلاد:</label>
      <input
        type="text"
        type="text"
        id="date de naissance"
        name="date de naissance"
        required
      />
      <br />
      <label for="الجنس:"></label><br />
      <select name="genre" id="genre" required>
        <br /><br />
        <option value="ذكر">ذكر</option>
        <option value="أنثى">أنثى</option></select
      ><br /><br />
      <label for="email">البريد الالكتروني:</label>
      <input type="email" id="email" name="email" required /> <br /><br />
      <label for="gouvernorat">الولاية:</label>
      <select name="gouvernorat" id="gouvernorat" required>
        <option value="تونس">تونس</option>
        <option value="بن عروس">بن عروس</option>
        <option value=" باجة">باجة</option>
        <option value=" المنستير">المنستير</option>
        <option value="المهدية">المهدية</option>
        <option value="سوسة">سوسة</option>
        <option value="جندوبة">جندوبة</option>
        <option value="القيروان">القيروان</option>
        <option value="سيدي بوزيد">سيدي بوزيد</option>
        <option value="القصرين">القصرين</option>
        <option value="الكاف">الكاف</option>
        <option value="مدنين">مدنين</option>
        <option value="توزر">توزر</option>
        <option value="تطاوين">تطاوين</option>
        <option value="اريانة">اريانة</option>
        <option value="بنزرت">بنزرت</option>
        <option value="زغوان">زغوان</option>
        <option value="سليانة">سليانة</option>
        <option value="صفاقس">صفاقس</option>
        <option value="قابس">قابس</option>
        <option value="قبلي">قبلي</option>
        <option value="قفصة">قفصة</option>
        <option value="نابل">نابل</option>
        <option value="منوبة">منوبة</option></select
      ><br /><br />
      <label for="avis">رأيك</label> <br />
      <textarea name="avis" id="avis" cols="50" rows="4" required></textarea>
      <br /><br />
      <label for="note">التقييم من( 1 الى 5):</label>
      <input type="number" id="note" name="note" min="1" max="5" required />
      <br /><br />
      <input type="submit" value="إرسال" />
    </form>
  </body>
</html>
