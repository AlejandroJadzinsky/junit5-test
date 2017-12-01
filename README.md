# junit5-test
JUnit5 PoC

given
- this test project

when 
- mvn test -Dtest=SingleMethodTest#firstMethod

then
- both test (firstMethod and secondMethod) are tested

expectd
- just firstMethod is tested
