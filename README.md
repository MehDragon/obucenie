{
  "branches": {
    "main": {
      "remoteTrackingBranchID": null,
      "remote": false,
      "target": "C4",
      "id": "main",
      "type": "branch"
    },
    "BugFix": {
      "remoteTrackingBranchID": null,
      "remote": false,
      "target": "C2",
      "id": "BugFix",
      "type": "branch"
    }
  },
  "commits": {
    "C0": {
      "type": "commit",
      "parents": [],
      "author": "Peter Cottle",
      "createTime": "Sat Dec 04 2021 09:59:10 GMT+0300 (Москва, стандартное время)",
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
      "createTime": "Sat Dec 04 2021 09:59:10 GMT+0300 (Москва, стандартное время)",
      "commitMessage": "Быстрый коммит. А надо!",
      "id": "C1"
    },
    "C2": {
      "type": "commit",
      "parents": [
        "C1"
      ],
      "author": "Peter Cottle",
      "createTime": "Sat Dec 04 2021 10:00:17 GMT+0300 (Москва, стандартное время)",
      "commitMessage": "Быстрый коммит. А надо!",
      "id": "C2"
    },
    "C3": {
      "type": "commit",
      "parents": [
        "C1"
      ],
      "author": "Peter Cottle",
      "createTime": "Sat Dec 04 2021 10:00:46 GMT+0300 (Москва, стандартное время)",
      "commitMessage": "Быстрый коммит. А надо!",
      "id": "C3"
    },
    "C4": {
      "type": "commit",
      "parents": [
        "C3",
        "C2"
      ],
      "author": "Peter Cottle",
      "createTime": "Sat Dec 04 2021 10:01:44 GMT+0300 (Москва, стандартное время)",
      "commitMessage": "Слияние branch \"BugFix\" в branch \"main\"",
      "id": "C4"
    }
  },
  "tags": {},
  "HEAD": {
    "id": "HEAD",
    "target": "main",
    "type": "general ref"
  }
}
