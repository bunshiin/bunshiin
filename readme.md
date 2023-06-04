```js
class Shuinore {
  constructor(...options) {
    this.height = "1.81"
    this.weight = "90"
    this.age = "17"
    this.type = "human"
    this.job = "student"
    this.sex = "male"
  }
}

class CreateMan extends bunshiin {
  constructor(...options) {
    super(options);
  }
  
  private _eating() {
    void "eating 🥩 🍷"
  }
  
  private _coding() {
    void "coding... ❤️"
  }
  
   private leraing() {
    void "leraing... 📖"
  }
  
  private _sleep(ms) { return new Promise(resolve => setTimeout(resolve, ms)) }
  
  async createDay() {
    this._eating();
    this._coding();
    await this._sleep(25200000);
    
    this.createDay();
  }
}

let bunshiin = new CreateMan()
bunshiin.createDay();
