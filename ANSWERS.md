## Questions

1. What is the difference between `new` and `create` for a model?
New create an empty object whereas create populates the object with data.

2. What command followed after with `Cat.new` will emulate the same behavior as `Cat.create`?
.create(params.require(:todo).permit(:tasks, :finished))

3. What is the default integer column that exists on every table but we did NOT define?
id

4. What single line of ruby code can insert a cat with the name "Kira" in the database?
Cat.create("Kira")

5. How did you like this homework in comparison with the previous homeworks?
harder!! :( ken told me it would be easier lol