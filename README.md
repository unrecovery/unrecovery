class unrecovery:

  def __init__(self):
    self.username = 'UNRECOVERY.DZ'
    self.name = 'Kevin Gabriel Rodriguez'
    self.age = 20
    self.city = 'Villahermosa, Mexico'
    self.email = 'unrecovery.dz@gmail.com'
    self.code = {
      'frontend': ['HTML','CSS','JavaScript','React'],
      'Backend': ['PHP', 'NodeJS','Python'],
      'database': ['MySQL','MongoDB','SQL Server'],
      'tools':['git','GitHub','Beekeeper Studio']
    }
    self.opsys = ['GNU/Linux', 'Microsoft Windows']

 def _str_(self):
    return self.name

 if __name__ == '__main__':
    me = unrecovery()
