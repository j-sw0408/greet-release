# Changelog

이 프로젝트의 주요 변경 사항을 이 파일에 기록한다.

형식은 [Keep a Changelog](https://keepachangelog.com/ko/1.1.0/)를 따르고, 이 프로젝트는 [유의적 버전](https://semver.org/lang/ko/)을 따른다.

## [Unreleased]

## [0.2.0] - 2026-11-09

### Added

- `greet()`에 `punctuation` 인수 추가: 이전에는 항상 `!`로 끝났지만 이제 `greet("Hee", ".")`처럼 끝 문장부호를 고를 수 있다(기본값 `!`).

### Fixed

- `greet()`의 빈 이름 처리: 빈 이름이나 공백만 있는 이름에 `Hello, !`를 반환하던 것을 `Hello, world!`로 고쳤다.

## [0.1.0] - 2026-11-09

### Added

- `greet()`와 명령행 인사말: 첫 번째 인수(없으면 `world`)에 `Hello, <name>!`을 출력한다.
