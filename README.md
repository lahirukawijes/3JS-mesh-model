# 3JS-mesh-model
Simple 3D mesh model created using 3JS

```
      function animate() {
        requestAnimationFrame(animate);

        sphere.rotation.x += 0.1;
        sphere.rotation.y += 0.01;
        sphere.rotation.z += 0.01;

        renderer.render(scene, camera);
      }
 ```
 You can change the rotation speed and direction by changing the x, y, z values in the above function.
