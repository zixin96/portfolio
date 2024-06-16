# Porfolio

```
npm install
npm start // this will start debug build
npm build // this will create a production build
```

Good references:

https://vilbeyli.github.io/games/

## DX12 Project

CZTODO:

Create an awesome looking scene that contains features like



### Chapter 9/10

- Animated materials by transforming texture coordinates
- Transparency by **alpha blending**
- Linear **fog**



### Chapter 11 

- planar mirror
  - learned how to **reflect** an object about an arbitrary plane
    - **winding order** changes for reflected objects
  - utilized **stencil buffer** to only render stuff in mirror
- planar shadows
  - learned how to use **general shadow matrix** to implement **point and directional planar shadow**
  - utilized **stencil buffer** to resolve **double blending**
  - learned how to resolve **z-flighting** between projected shadow meshes and the plane
