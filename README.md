# Property-specification
 
var sampleObject = {
 hello: 'world'
};
Object.getOwnPropertyDescriptor(sampleObject, 'hello');
// Object {value: "world", writable: true, enumerable: true, configurable: true}
