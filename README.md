# Grunt vs Gulp

## Gulp
    1. Focuses on code
    2. enforces nothing, all community developed micro-tasks
    3. uses streams and builds complex pipelines
    4. uses nodes
    5. executes faster since it does not open or close files
    6. uses a virtual file object called  Vinyl (abstraction)
    7. gulp plugins try to do 1 thing well
        1. complex tasks should involve multiple plugins
    8. cult is less coupled than grunt since every plugin is a node streaming module
    9. “One word of advice though is to try not to fit every piece of your code into a Gulp plugin. As this article points out, thinking of your code as a Gulp plugin would inevitably increase configuration, which is counter to what the Gulp guidelines, and the do one thing well philosophy suggest. This is where the code over configuration principle shines. Unlike Grunt, Gulp makes it extremely easy to fit other code within a task definition, besides streaming from one plugin to another. In fact, a Gulp task may not even contain a streaming pipeline”
    10. Get started: https://scotch.io/tutorials/automate-your-tasks-easily-with-gulp-js

## Grunt
    1. Focuses on configuration
    2. Built around a set of built-in and commonly used tasks
    3. is relatively slower
    4. takes double the effort to create tasks with clean and concat
    5. builds temp files
    6. Learn how to grunt here: http://gruntjs.com/getting-started

## Conclusion
    1. Both have a large amount of support
    2. Gulp community is growing faster
    3. Grunt community is still strong
    4. gulp is easier to write
    5. grunt requires less time thinking about theory
    6. gulp is faster
    7. ultimately it comes down to preference
