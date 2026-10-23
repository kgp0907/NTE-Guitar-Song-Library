# NTE Guitar Shared Song Library

Read-only catalog for the NTE Guitar shared-song browser. The application source code is maintained separately and is not included here.

## Initial test library

The initial catalog contains three newly generated short integration-test phrases, covering performance-only notes, editable note source, and MIDI source. They are test material rather than arrangements of existing songs. See `TEST-MATERIAL-LICENSE.txt`.

The client verifies the HTTPS destination, file size and SHA-256, then runs its existing offline `.ntesong` validation and importer. Previewing does not register a local song. Adding a song uses a new local slot.

## 한국어 안내

NTE Guitar의 **공유 곡** 창에서 목록을 불러오고, 미리 듣거나 내 곡에 추가할 수 있습니다. 처음 공개되는 자료는 동작 확인용 짧은 테스트 선율 3개입니다.

곡 제출 경로는 준비 중입니다. 프로그램은 자동 업로드하지 않습니다. 공개 재배포 허용 근거를 확인한 자료만 운영자가 등록합니다. 원본 MIDI뿐 아니라 변환한 음표 데이터도 확인 대상입니다.

Catalog: `catalog.json` on the `main` branch. Approved packages: GitHub Releases assets.

No submission credentials, personal settings, private permission evidence, or existing user library are included.
