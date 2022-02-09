```
➜  rbs git:(master) ✗ bundle exec steep check
# Type checking files:

.................................................F............

lib/rbs.rb:9:8: [error] Cannot pass a value of type `::Integer` as an argument of type `::String`
│   ::Integer <: ::String
│     ::Numeric <: ::String
│       ::Object <: ::String
│         ::BasicObject <: ::String
│
│ Diagnostic ID: Ruby::ArgumentTypeMismatch
│
└ Rbs.new(1)
          ~

Detected 1 problem from 1 file
```