
use new
switched to db new
db.cl.insertOne({name:"Karthik",age:18,gender:"M"});
{
  acknowledged: true,
  insertedId: ObjectId("6492718dd6a9945d39427394")
}
db.cl.insertOne({name:"Srithika",age:21,gender:"F"});
{
  acknowledged: true,
  insertedId: ObjectId("649271afd6a9945d39427395")
}
db.cl.insertOne({name:"Haritha",age:19,gender:"F"});
{
  acknowledged: true,
  insertedId: ObjectId("64927250d6a9945d39427396")
}
db.cl.insertOne({name:"Bharath",age:27,gender:"M"});
{
  acknowledged: true,
  insertedId: ObjectId("6492726ed6a9945d39427397")
}
db.cl.insertOne({name:"Aarish",age:15,gender:"M"});
{
  acknowledged: true,
  insertedId: ObjectId("64927282d6a9945d39427398")
}
db.cl.insertOne({name:"Dev",age:19,gender:"M"});
{
  acknowledged: true,
  insertedId: ObjectId("649272b0d6a9945d39427399")
}
db.cl.insertOne({name:"Aishwarya",age:16,gender:"F"});
{
  acknowledged: true,
  insertedId: ObjectId("649272cad6a9945d3942739a")
}
db.cl.find();
{
  _id: ObjectId("6492718dd6a9945d39427394"),
  name: 'Karthik',
  age: 18,
  gender: 'M'
}
{
  _id: ObjectId("649271afd6a9945d39427395"),
  name: 'Srithika',
  age: 21,
  gender: 'F'
}
{
  _id: ObjectId("64927250d6a9945d39427396"),
  name: 'Haritha',
  age: 19,
  gender: 'F'
}
{
  _id: ObjectId("6492726ed6a9945d39427397"),
  name: 'Bharath',
  age: 27,
  gender: 'M'
}
{
  _id: ObjectId("64927282d6a9945d39427398"),
  name: 'Aarish',
  age: 15,
  gender: 'M'
}
{
  _id: ObjectId("649272b0d6a9945d39427399"),
  name: 'Dev',
  age: 19,
  gender: 'M'
}
{
  _id: ObjectId("649272cad6a9945d3942739a"),
  name: 'Aishwarya',
  age: 16,
  gender: 'F'
}
db.cl.find({age:{$gt:30}});
db.cl.find();
{
  _id: ObjectId("6492718dd6a9945d39427394"),
  name: 'Karthik',
  age: 18,
  gender: 'M'
}
{
  _id: ObjectId("649271afd6a9945d39427395"),
  name: 'Srithika',
  age: 21,
  gender: 'F'
}
{
  _id: ObjectId("64927250d6a9945d39427396"),
  name: 'Haritha',
  age: 19,
  gender: 'F'
}
{
  _id: ObjectId("6492726ed6a9945d39427397"),
  name: 'Bharath',
  age: 27,
  gender: 'M'
}
{
  _id: ObjectId("64927282d6a9945d39427398"),
  name: 'Aarish',
  age: 15,
  gender: 'M'
}
{
  _id: ObjectId("649272b0d6a9945d39427399"),
  name: 'Dev',
  age: 19,
  gender: 'M'
}
{
  _id: ObjectId("649272cad6a9945d3942739a"),
  name: 'Aishwarya',
  age: 16,
  gender: 'F'
}
db.cl.find({age:{$gt:15}});
{
  _id: ObjectId("6492718dd6a9945d39427394"),
  name: 'Karthik',
  age: 18,
  gender: 'M'
}
{
  _id: ObjectId("649271afd6a9945d39427395"),
  name: 'Srithika',
  age: 21,
  gender: 'F'
}
{
  _id: ObjectId("64927250d6a9945d39427396"),
  name: 'Haritha',
  age: 19,
  gender: 'F'
}
{
  _id: ObjectId("6492726ed6a9945d39427397"),
  name: 'Bharath',
  age: 27,
  gender: 'M'
}
{
  _id: ObjectId("649272b0d6a9945d39427399"),
  name: 'Dev',
  age: 19,
  gender: 'M'
}
{
  _id: ObjectId("649272cad6a9945d3942739a"),
  name: 'Aishwarya',
  age: 16,
  gender: 'F'
}
db.cl.find().sort({age:-1});
{
  _id: ObjectId("6492726ed6a9945d39427397"),
  name: 'Bharath',
  age: 27,
  gender: 'M'
}
{
  _id: ObjectId("649271afd6a9945d39427395"),
  name: 'Srithika',
  age: 21,
  gender: 'F'
}
{
  _id: ObjectId("64927250d6a9945d39427396"),
  name: 'Haritha',
  age: 19,
  gender: 'F'
}
{
  _id: ObjectId("649272b0d6a9945d39427399"),
  name: 'Dev',
  age: 19,
  gender: 'M'
}
{
  _id: ObjectId("6492718dd6a9945d39427394"),
  name: 'Karthik',
  age: 18,
  gender: 'M'
}
{
  _id: ObjectId("649272cad6a9945d3942739a"),
  name: 'Aishwarya',
  age: 16,
  gender: 'F'
}
{
  _id: ObjectId("64927282d6a9945d39427398"),
  name: 'Aarish',
  age: 15,
  gender: 'M'
}
db.cl.find().sort({age:1});
{
  _id: ObjectId("64927282d6a9945d39427398"),
  name: 'Aarish',
  age: 15,
  gender: 'M'
}
{
  _id: ObjectId("649272cad6a9945d3942739a"),
  name: 'Aishwarya',
  age: 16,
  gender: 'F'
}
{
  _id: ObjectId("6492718dd6a9945d39427394"),
  name: 'Karthik',
  age: 18,
  gender: 'M'
}
{
  _id: ObjectId("64927250d6a9945d39427396"),
  name: 'Haritha',
  age: 19,
  gender: 'F'
}
{
  _id: ObjectId("649272b0d6a9945d39427399"),
  name: 'Dev',
  age: 19,
  gender: 'M'
}
{
  _id: ObjectId("649271afd6a9945d39427395"),
  name: 'Srithika',
  age: 21,
  gender: 'F'
}
{
  _id: ObjectId("6492726ed6a9945d39427397"),
  name: 'Bharath',
  age: 27,
  gender: 'M'
}
db.cl.find().sort({age:1},{name:-1},{gender:1});
{
  _id: ObjectId("64927282d6a9945d39427398"),
  name: 'Aarish',
  age: 15,
  gender: 'M'
}
{
  _id: ObjectId("649272cad6a9945d3942739a"),
  name: 'Aishwarya',
  age: 16,
  gender: 'F'
}
{
  _id: ObjectId("6492718dd6a9945d39427394"),
  name: 'Karthik',
  age: 18,
  gender: 'M'
}
{
  _id: ObjectId("64927250d6a9945d39427396"),
  name: 'Haritha',
  age: 19,
  gender: 'F'
}
{
  _id: ObjectId("649272b0d6a9945d39427399"),
  name: 'Dev',
  age: 19,
  gender: 'M'
}
{
  _id: ObjectId("649271afd6a9945d39427395"),
  name: 'Srithika',
  age: 21,
  gender: 'F'
}
{
  _id: ObjectId("6492726ed6a9945d39427397"),
  name: 'Bharath',
  age: 27,
  gender: 'M'
}
db.cl.find().sort({name:-1},{gender:1});
{
  _id: ObjectId("649271afd6a9945d39427395"),
  name: 'Srithika',
  age: 21,
  gender: 'F'
}
{
  _id: ObjectId("6492718dd6a9945d39427394"),
  name: 'Karthik',
  age: 18,
  gender: 'M'
}
{
  _id: ObjectId("64927250d6a9945d39427396"),
  name: 'Haritha',
  age: 19,
  gender: 'F'
}
{
  _id: ObjectId("649272b0d6a9945d39427399"),
  name: 'Dev',
  age: 19,
  gender: 'M'
}
{
  _id: ObjectId("6492726ed6a9945d39427397"),
  name: 'Bharath',
  age: 27,
  gender: 'M'
}
{
  _id: ObjectId("649272cad6a9945d3942739a"),
  name: 'Aishwarya',
  age: 16,
  gender: 'F'
}
{
  _id: ObjectId("64927282d6a9945d39427398"),
  name: 'Aarish',
  age: 15,
  gender: 'M'
}
db.cl.find().sort({gender:1});
{
  _id: ObjectId("649271afd6a9945d39427395"),
  name: 'Srithika',
  age: 21,
  gender: 'F'
}
{
  _id: ObjectId("64927250d6a9945d39427396"),
  name: 'Haritha',
  age: 19,
  gender: 'F'
}
{
  _id: ObjectId("649272cad6a9945d3942739a"),
  name: 'Aishwarya',
  age: 16,
  gender: 'F'
}
{
  _id: ObjectId("6492718dd6a9945d39427394"),
  name: 'Karthik',
  age: 18,
  gender: 'M'
}
{
  _id: ObjectId("6492726ed6a9945d39427397"),
  name: 'Bharath',
  age: 27,
  gender: 'M'
}
{
  _id: ObjectId("64927282d6a9945d39427398"),
  name: 'Aarish',
  age: 15,
  gender: 'M'
}
{
  _id: ObjectId("649272b0d6a9945d39427399"),
  name: 'Dev',
  age: 19,
  gender: 'M'
}
new
