
 #### How to set up a project in a few cmd

 
```
     npm init
     npm install react react-dom --save
     npm install mocha expect react-addons-test-utils --save-dev
     npm install babel-core babel-preset-es2015 --save-dev
```

Create the .babelrc file

```
    {
      "presets": ["es2015"]
    }
```


Create the most basic spec file

```

    import expect from 'expect';
    
    describe('empty', () => {
      it('should work', () => {
        expect(true).toEqual(true);
      })
    });
```