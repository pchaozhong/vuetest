<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <title>vue test</title>
    <script src="https://code.jquery.com/jquery-3.3.1.js"></script>
<script src="https://cdn.datatables.net/1.10.16/js/jquery.dataTables.min.js"></script>
<script src="https://cdn.datatables.net/1.10.16/js/dataTables.bootstrap4.min.js"></script>
 <link rel="stylesheet" type="text/css" href="https://cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/4.0.0/css/bootstrap.css">
</head>
<script>
$(document).ready(function() {
    $('#example').DataTable();
} );
</script>
<body>
<form>
<table id="example" class="table table-striped table-bordered" style="width:100%">
        <thead>
            <tr>
                <th>对战时间</th>
                <th>对战国A</th>
                <th>对战国B</th>
                <th>所在Group</th>
                <th>竞猜结果</th>
 	<th>数量</th>
	<th>操作</th>

            </tr>
        </thead>
        <tbody>
            <tr>
                <td>0628-18:00</td>
                <td>System Architect</td>
                <td>Edinburgh</td>
                <td>61</td>
 <td>
      <input type="radio" name="gakunen" value="won">胜
      <input type="radio" name="gakunen" value="peache">平
      <input type="radio" name="gakunen" value="fair">负
    </td>
	<td><input type="text" name="name" size="10" maxlength="10"></td>
	<td><input type="submit" value="决定"></td>


            </tr>
            <tr>
                <td>0628-19:00</td>
                <td>Accountant</td>
                <td>Tokyo</td>
                <td>63</td>
 <td>
      <input type="radio" name="gakunen" value="won">胜
      <input type="radio" name="gakunen" value="peache">平
      <input type="radio" name="gakunen" value="fair">负
    </td>
<td><input type="text" name="name" size="10" maxlength="10"></td>
<td><input type="submit" value="决定"></td>

            </tr>
            <tr>
                <td>0614-18:00</td>
                <td>Junior Technical Author</td>
                <td>San Francisco</td>
                <td>66</td>
 <td>
      <input type="radio" name="gakunen" value="won">胜
      <input type="radio" name="gakunen" value="peache">平
      <input type="radio" name="gakunen" value="fair">负
    </td>
<td><input type="text" name="name" size="10" maxlength="10"></td>
<td><input type="submit" value="决定"></td>

            </tr>
            <tr>
                <td>0615-18:00</td>
                <td>Senior Javascript Developer</td>
                <td>Edinburgh</td>
                <td>22</td>
 <td>
      <input type="radio" name="gakunen" value="won">胜
      <input type="radio" name="gakunen" value="peache">平
      <input type="radio" name="gakunen" value="fair">负
    </td>
<td><input type="text" name="name" size="10" maxlength="10"></td>
<td><input type="submit" value="决定"></td>

            </tr>
            <tr>
                <td>0614-18:00</td>
                <td>Accountant</td>
                <td>Tokyo</td>
                <td>33</td>
 <td>
      <input type="radio" name="gakunen" value="won">胜
      <input type="radio" name="gakunen" value="peache">平
      <input type="radio" name="gakunen" value="fair">负
    </td>
<td><input type="text" name="name" size="10" maxlength="10"></td>
<td><input type="submit" value="决定"></td>
            </tr>
        </tbody>

    </table>
</form>

<link rel="stylesheet" type="text/css" href="https://cdn.datatables.net/1.10.16/css/dataTables.bootstrap4.min.css">
</body>
</html>
