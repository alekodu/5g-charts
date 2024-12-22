Make sure to change in mongodb deployment persistent for ephimeral storage on memory:

volumes:
  - name: datadir
    emptyDir:
      sizeLimit: 500Mi
      medium: Memory
