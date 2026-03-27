import express from "express";

const app = express();

app.get("/", (req, res) => {
  res.send("Servidor activo");
});

const port = process.env.PORT || 3000;

app.listen(port, () => {
  console.log("Server corriendo en puerto " + port);
});
