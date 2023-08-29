class SimpleClassifier(nn.Module):

    def __init__(self, num_inputs, num_hidden, num_outputs):
        super().__init__()
        self.linear1 = nn.Linear(num_inputs, num_hidden)
        self.act_fn = nn.Tanh() THIS DEFINES THE ACTIVATION FUNCTION
        self.linear2 = nn.Linear(num_hidden, num_outputs)