# Definitions

## Clean Code

Definition from Robert C. Martin (Uncle Bob):

1. It should be elegant 

- Clean code should be pleasing to read. Reading it should make you smile the way a well-crafted music box or well-designed car would.
- Make your software readable for humans, not for computers.

2. Clean code is focused

- Each function, each class, each module exposes a single-minded attitude that remains entirely undistracted, and unpolluted, by the surrounding details.
 
3. Clean code is taken care of. Someone has taken the time to keep it simple and orderly. They have paid appropriate attention to details. They have cared.

4. Runs all the tests

5. Contains no duplication

6. Minimize the number of entities such as classes, methods, functions, and the like.

## Dependency Injection

To instanciate a [service](https://github.com/boeschenstein/definition/tree/master#what-is-a-service), you should never do this manually (with new). You better have your service instanciated automatically. You'll find a lot of reasons when you read about [Clean Code](https://github.com/boeschenstein/definition/tree/master#clean-code)

## Monorepo

Manfred Steyer:

- C# developer use monorepos all the time: a solution is a monorepo. Advantages: no version issues between libraries.
- Angular: see nx from nrwl.

## What is a service

This is a more sophisticated term for a simple class. This term was invented to confuse people.
