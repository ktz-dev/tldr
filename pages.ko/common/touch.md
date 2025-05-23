# touch

> 파일을 생성하고 접근/수정 시간을 설정합니다.
> 더 많은 정보: <https://manned.org/touch>.

- 특정 파일 생성:

`touch {{경로/대상/파일1 경로/대상/파일2 ...}}`

- 파일의 [a]ccess 또는 [m]odification 시간을 현재 시간으로 설정하고 파일이 없으면 [c]reate 하지 않음:

`touch {{[-c|--no-create]}} -{{a|m}} {{경로/대상/파일1 경로/대상/파일2 ...}}`

- 파일의 [t]ime을 특정 값으로 설정하고 파일이 없으면 [c]reate 하지 않음:

`touch {{[-c|--no-create]}} -t {{YYYYMMDDHHMM.SS}} {{경로/대상/파일1 경로/대상/파일2 ...}}`

- 파일의 타임스탬프를 [r]eference 파일의 타임스탬프로 설정하고 파일이 없으면 [c]reate 하지 않음:

`touch {{[-c|--no-create]}} {{[-r|--reference]}} {{경로/대상/참조_파일}} {{경로/대상/파일1 경로/대상/파일2 ...}}`
