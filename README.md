{
  "branches": {
    "main": {
      "remoteTrackingBranchID": null,
      "remote": false,
      "target": "C5",
      "id": "main",
      "type": "branch"
    },
    "side": {
      "remoteTrackingBranchID": null,
      "remote": false,
      "target": "C3",
      "id": "side",
      "type": "branch"
    }
  },
  "commits": {
    "C0": {
      "type": "commit",
      "parents": [],
      "author": "Peter Cottle",
      "createTime": "Sat Dec 04 2021 12:00:30 GMT+0300 (Москва, стандартное время)",
      "commitMessage": "Быстрый коммит. А надо!",
      "id": "C0",
      "rootCommit": true
    },
    "C1": {
      "type": "commit",
      "parents": [
        "C0"
      ],
      "author": "Peter Cottle",
      "createTime": "Sat Dec 04 2021 12:00:30 GMT+0300 (Москва, стандартное время)",
      "commitMessage": "Быстрый коммит. А надо!",
      "id": "C1"
    },
    "C2": {
      "type": "commit",
      "parents": [
        "C1"
      ],
      "author": "Peter Cottle",
      "createTime": "Sat Dec 04 2021 12:00:30 GMT+0300 (Москва, стандартное время)",
      "commitMessage": "Быстрый коммит. А надо!",
      "id": "C2"
    },
    "C3": {
      "type": "commit",
      "parents": [
        "C2"
      ],
      "author": "Peter Cottle",
      "createTime": "Sat Dec 04 2021 12:00:30 GMT+0300 (Москва, стандартное время)",
      "commitMessage": "Быстрый коммит. А надо!",
      "id": "C3"
    },
    "C4": {
      "type": "commit",
      "parents": [
        "C1"
      ],
      "author": "Peter Cottle",
      "createTime": "Sat Dec 04 2021 12:00:30 GMT+0300 (Москва, стандартное время)",
      "commitMessage": "Быстрый коммит. А надо!",
      "id": "C4"
    },
    "C5": {
      "type": "commit",
      "parents": [
        "C2",
        "C4"
      ],
      "author": "Peter Cottle",
      "createTime": "Sat Dec 04 2021 12:00:30 GMT+0300 (Москва, стандартное время)",
      "commitMessage": "Быстрый коммит. А надо!",
      "id": "C5"
    }
  },
  "tags": {
    "v0": {
      "target": "C1",
      "id": "v0",
      "type": "tag"
    },
    "v1": {
      "target": "C2",
      "id": "v1",
      "type": "tag"
    }
  },
  "HEAD": {
    "target": "C2",
    "id": "HEAD",
    "type": "general ref"
  }
}
