```python
class Notes:
	def __init__(self, []):
		self.list_of_notes = 
		
	def find(key_word):
		key = key_word
		result = 
		for note in self.list_of_notes:
			if key in note.title
				result.append(note)
		return result 

class Note:
    def __init__(self, content):
	    note.title
        self.content = content  # Contents of notes
        self.in_category = []   # Belongs to which category
        self.up = []            # From which note
        self.down = []          # Which notes are affected
        self.similar = []       # Which notes are similar to
        self.opposite = []      # Contrary to which note

    def add_in_category(self, category_note):
        self.in_category.append(category_note)

    def add_up(self, source_note):
        self.up.append(source_note)

    def add_down(self, influenced_note):
        self.down.append(influenced_note)

    def add_similar(self, similar_note):
        self.similar.append(similar_note)

    def add_opposite(self, opposite_note):
        self.opposite.append(opposite_note)

# usage example
note1 = Note("Note 1")
note2 = Note("Note 2")
note3 = Note("Note 3")

# Setting up the relationship
note1.add_down(note2)  # note1 affects note2
note2.add_up(note1)    # note2 from note1
note2.add_similar(note3)  # note2 similar to note3
note1.add_opposite(note3)  # note1 as opposed to note3

```

## Question:

simple first: 

搜索和查询能力：如何设计一个功能，能够根据所有笔记内容查找笔记名字

持久化存储：如何长期储存

如何建立文件夹用代码怎么表示？

## To-do list:
