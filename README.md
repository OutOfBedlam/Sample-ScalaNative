
* 2017/3/15일 릴리즈된 scala-native 0.1버전에 대한 HelloWorld 예제입니다.

**SBT Tasks**

지원되는 sbt task는 다음과 같습니다.

 - compile
 - nativeLink
 - run
 - package
 - publish
 
 
**SBT settings**

 - `nativeClang`: `File`  -> `clang` 명령어의 경로
 - `nativeClangPP`: `File` -> `clang++` 명령어의 경로
 - `nativeCompileOptions`: `Seq[String]` clang에 전달할 추가 옵션들
 - `nativeMode`: `String` -> `debug`(디폴트), `release`
 
더 자세한 사항은 [http://www.scala-native.org/](http://www.scala-native.org/)을 참조
