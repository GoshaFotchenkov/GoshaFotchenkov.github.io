<!DOCTYPE html>
<html>
  <head>
    <title>Instrumental Extractor</title>
  </head>
  <body>
    <h1>Instrumental Extractor</h1>
    <form action="/extract" method="post" enctype="multipart/form-data">
      <label for="songFile">Select a song file:</label>
      <input type="file" id="songFile" name="songFile" accept=".mp3,.wav" required><br><br>
      <label for="startPoint">Select a starting point:</label>
      <input type="number" id="startPoint" name="startPoint" min="0" max="9999" value="0"><br><br>
      <label for="endPoint">Select an ending point:</label>
      <input type="number" id="endPoint" name="endPoint" min="0" max="9999" value="9999"><br><br>
      <button type="submit">Extract Instrumental</button>
    </form>
  </body>
</html>
